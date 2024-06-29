202405221823
Status: #study 
Tags:
[[Java]], [[Coding]], [[bootCampSantander]]

# Java Stream API 1- Imperativa X Declarativa
- A Streams API traz uma nova opção para a manipulação de coleções em Java seguindo os princípios da programação funcional.
- Stream, trata-se de uma poderosa solução para processar coleções de maneira declarativa, ao invés da tradicional e burocrática forma imperativa.
```Java
public class CarrinhoDeCompras {
  //atributos
  private List<Item> itemList;
  //construtor
  public CarrinhoDeCompras() {
    this.itemList = new ArrayList<>();
  }
  
  //método para calcular valor total dos itens sem utilizar o Stream API
  public double calcularValorTotal() {
    double valorTotal = 0d;
    if (!itemList.isEmpty()) {
      for (Item item : itemList) {
        double valorItem = item.getPreco() * item.getQuant();
        valorTotal += valorItem;
      }
      return valorTotal;
    } else {
      throw new RuntimeException("A lista está vazia!");
    }
  }
}
```

- Na forma imperativa, para realizar uma soma simples, por exemplo, o desenvolvedor tem que se preocupar não apenas com o que deve ser feito em cada elemento, isto é, com as regras associadas ao processamento dos elementos da lista, mas também com a maneira de realizar essa iteração.
```Java
public class CarrinhoDeCompras {
  //atributos
  private List<Item> itemList;
  //construtor
  public CarrinhoDeCompras() {
    this.itemList = new ArrayList<>();
  }
  
  //método para calcular valor total dos itens utilizando o Stream API
  public double calcularValorTotal() {
    if (itemList.isEmpty()) {
      throw new RuntimeException("A lista está vazia!");
    }
    return itemList.stream()
        .mapToDouble(item -> item.getPreco() * item.getQuant())
        .sum();
  }
}
```
- Combinada com as Expressões Lambda e Method reference, eles proporcionam uma forma diferente de lidar com conjuntos de elementos, oferecendo ao desenvolvedor uma maneira simples e concisa de escrever código que resulta em facilidade de manutenção e paralelização sem efeitos indesejados em tempo de execução.
- As operações na Stream API podem ser classificadas em duas categorias principais:
	 1. Operações Intermediárias: são aquelas que retornam uma nova Stream e permitem encadear várias operações, formando um pipeline de processamento de dados. São elas:
		- `filter(Predicate<T> predicate)`: Filtra os elementos da Stream com base em um predicado. Retorna uma nova Stream contendo apenas os elementos que atendem ao critério do predicado. Exemplo:  `stream.filter(n -> n > 5)`
		- `map(Function<T, R> mapper)`: Transforma cada elemento da Stream usando a função especificada e retorna uma nova Stream contendo os elementos resultantes. Exemplo: `stream.map(s -> s.toUpperCase())`
		- `sorted()`: Classifica os elementos da Stream em ordem natural (se os elementos forem comparáveis) ou de acordo com um comparador fornecido. Exemplo: `stream.sorted()`
		- `distinct()`: Remove elementos duplicados da Stream, considerando a implementação do método equals() para comparação. Exemplo: `stream.distinct()`
		- `limit(long maxSize)`: Limita o número de elementos da Stream aos maxSize primeiros elementos Exemplo: stream.limit(10)
		- `skip(long n)`: Pula os primeiros n elementos da Stream e retorna uma nova Stream sem eles. Exemplo: `stream.skip(5)`
	2. Operações Terminais: são aquelas que encerram o pipeline e produzem um resultado final. São elas:
		- `forEach(Consumer<T> action)`: Executa uma ação para cada elemento da Stream. Exemplo: `stream.forEach(System.out::println)`
		- `toArray()`: Converte a Stream em um array contendo os elementos da Stream. Exemplo: `stream.toArray()`
		- `collect(Collector<T, A, R> collector)`: Coleta os elementos da Stream em uma estrutura de dados específica, como uma lista ou um mapa. Exemplo: stream.collect(Collectors.toList())
		- `count()`: Retorna o número de elementos na Stream. Exemplo: `stream.count()`
		- `anyMatch(Predicate<T> predicate)`: Verifica se algum elemento da Stream atende ao predicado especificado. Exemplo: `stream.anyMatch(s -> s.startsWith("A"))`
		- `allMatch(Predicate<T> predicate)`: Verifica se todos os elementos da Stream atendem ao predicado especificado. Exemplo: `stream.allMatch(n -> n > 0)`
		- `noneMatch(Predicate<T> predicate)`: Verifica se nenhum elemento da Stream atende ao predicado especificado. Exemplo: stream.noneMatch(s -> s.isEmpty())
		- `min(Comparator<T> comparator)` e `max(Comparator<T> comparator)`: Encontra o elemento mínimo e máximo da Stream, respectivamente, de acordo com o comparador fornecido. Exemplo: `stream.min(Comparator.naturalOrder())` ou `stream.max(Comparator.naturalOrder())`
		- `reduce(T identity, BinaryOperator<T> accumulator)`: Combina os elementos da Stream usando o acumulador especificado e retorna o resultado final. Exemplo: `stream.reduce(0, (a, b) -> a + b)`

___
# References
- [Camila DIO - Stream API](https://github.com/digitalinnovationone/ganhando_produtividade_com_Stream_API_Java)
- [Java Stream API - Oracle](https://www.oracle.com/br/technical-resources/articles/java-stream-api.html)
