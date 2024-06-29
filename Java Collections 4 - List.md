202405201618
Status: #study 
Tags:
[[Java]], [[bootCampSantander]], [[Coding]]
# Java Collections 4 - List

- A interface `List` é uma coleção ordenada que permite a inclusão de elementos duplicados.
- É um dos tipos mais utilizados em Java, e as classes de implementação comuns são `ArrayList` e `LinkedList`.
- `List` se assemelha a uma matrix com comprimento dinâmico, permitindo adicionar ou remover elementos.
- A interface `List` fornece métodos úteis para adicionar elementos em posições específicas, remover ou substituir elementos com base no índice e obter sublistas usando usando índices.
- A classe `Colections` fornece algoritmos úteis para manipulação de `List`, como `sort` (ordenação), `shuffle` embaralhamento, `reverse` (reversão) e `binarySearch` (busca binária).

> _ArrayList_: O ArrayList é uma implementação da interface List que armazena os elementos em uma estrutura de array redimensionável. Isso significa que ele pode crescer automaticamente à medida que novos elementos são adicionados. A principal vantagem do ArrayList é o acesso rápido aos elementos por meio de índices, o que permite recuperar um elemento específico de forma eficiente. No entanto, adicionar ou remover elementos no meio da lista pode ser mais lento, pois requer a realocação de elementos.

> _LinkedList_: O LinkedList é uma implementação da interface List que armazena os elementos em uma lista duplamente vinculada. Cada elemento contém referências para o elemento anterior e próximo na lista. A principal vantagem do LinkedList é a eficiência na adição ou remoção de elementos no início ou no final da lista, pois não é necessário realocar elementos. No entanto, o acesso aos elementos por meio de índices é mais lento, pois requer percorrer a lista até o elemento desejado.
 
> _Vector_: O Vector é uma implementação antiga da interface List que é semelhante ao ArrayList, mas é sincronizada, ou seja, é thread-safe. Isso significa que várias threads podem manipular um objeto Vector ao mesmo tempo sem causar problemas de concorrência. No entanto, essa sincronização adiciona uma sobrecarga de desempenho, tornando o Vector menos eficiente do que o ArrayList em cenários em que a concorrência não é um problema. Por esse motivo, o uso do Vector é menos comum em aplicações modernas.


___
# References
[📝 Camila Instrutora DIO](https://github.com/cami-la/collections-java-api-2023/tree/master/src/main/java/list#arraylist-o-arraylist-%C3%A9-uma-implementa%C3%A7%C3%A3o-da-interface-list-que-armazena-os-elementos-em-uma-estrutura-de-array-redimension%C3%A1vel-isso-significa-que-ele-pode-crescer-automaticamente-%C3%A0-medida-que-novos-elementos-s%C3%A3o-adicionados-a-principal-vantagem-do-arraylist-%C3%A9-o-acesso-r%C3%A1pido-aos-elementos-por-meio-de-%C3%ADndices-o-que-permite-recuperar-um-elemento-espec%C3%ADfico-de-forma-eficiente-no-entanto-adicionar-ou-remover-elementos-no-meio-da-lista-pode-ser-mais-lento-pois-requer-a-realoca%C3%A7%C3%A3o-de-elementos)