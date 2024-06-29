202405201631
Status: #study
Tags:
[[Java]], [[bootCampSantander]], [[Coding]]
# Java Collections 6 - Map
- A interface `Map` é usada para mapear dados na forma de chaves e valores.
- O `Map` do Java é um objeto que mapeia chaves para valores.
- Um `Map` não pode conter chaves duplicadas: cada chave pode mapear no máximo um valor.
- A plataforma Java possui três implementações gerais de `Map`: `HashMap`, `TreeMap` e `LinkedHashMap`.
- As operações básicas do `Map` são: `put` (inserir ou atualizar), `get` (obter), `containsKey` (verificar se contém uma chave), `containsValue` (verificar se contém um valor), `size` (obter o tamanho) e `isEmpty` (verificar se está vazio).

>_HashTable_ é uma implementação antiga da interface Map no Java que é sincronizada e thread-safe, tornando-a adequada para uso em ambientes concorrentes. Ela não permite chaves ou valores nulos e os elementos não são mantidos em uma ordem específica.
> 

> _LinkedHashMap_, por outro lado, é uma implementação da interface Map que preserva a ordem de inserção dos elementos. Cada elemento possui referências ao próximo e ao anterior, formando uma lista encadeada. Isso permite que os elementos sejam iterados na ordem em que foram inseridos. Além disso, o LinkedHashMap também permite chaves ou valores nulos.

> _HashMap_ é uma implementação da interface Map que não mantém uma ordem específica dos elementos. Ele armazena os elementos internamente usando uma função de hash para melhorar a eficiência das operações de pesquisa e acesso. O HashMap também permite chaves ou valores nulos.





___
# References
[📝 Camila Instrutora DIO](https://github.com/cami-la/collections-java-api-2023/tree/master/src/main/java/list#arraylist-o-arraylist-%C3%A9-uma-implementa%C3%A7%C3%A3o-da-interface-list-que-armazena-os-elementos-em-uma-estrutura-de-array-redimension%C3%A1vel-isso-significa-que-ele-pode-crescer-automaticamente-%C3%A0-medida-que-novos-elementos-s%C3%A3o-adicionados-a-principal-vantagem-do-arraylist-%C3%A9-o-acesso-r%C3%A1pido-aos-elementos-por-meio-de-%C3%ADndices-o-que-permite-recuperar-um-elemento-espec%C3%ADfico-de-forma-eficiente-no-entanto-adicionar-ou-remover-elementos-no-meio-da-lista-pode-ser-mais-lento-pois-requer-a-realoca%C3%A7%C3%A3o-de-elementos)