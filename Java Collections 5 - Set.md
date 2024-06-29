202405201629
Status: #study
Tags:
[[Java]], [[bootCampSantander]], [[Coding]]
# Java Collections 5 - Set

- A interface `Set` é uma coleção que não pode conter elementos duplicados.
- Essa interface representa o conceito matemático de um conjunto e é usada para representar conjuntos, como um baralho de cartas.
- A plataforma Java possui três implementações de `Set` de uso geral: `HashSet`, `TreeSet` e `LinkedHashSet`.
- A interface `Set` não permite acesso aleatório a um elemento na coleção.
- Para percorrer os elementos de um `Set`, você pode usar um iterador ou um loop foreach.

>_HashSet_: O HashSet é uma implementação da interface Set que armazena os elementos em uma tabela hash. Ele não mantém uma ordem específica dos elementos. A principal vantagem do HashSet é que ele oferece um desempenho de busca muito eficiente, pois usa funções hash para indexar os elementos. No entanto, a ordem em que os elementos são adicionados pode não ser preservada ao percorrer o conjunto.
 
>  _TreeSet_: O TreeSet é uma implementação da interface Set que armazena os elementos em uma árvore binária balanceada. Isso significa que os elementos são armazenados em uma ordem classificada e são mantidos automaticamente em ordem crescente. A principal vantagem do TreeSet é que os elementos são sempre retornados na ordem classificada, o que facilita a obtenção de elementos em uma determinada ordem. No entanto, a busca e a inserção são um pouco mais lentas em comparação com o HashSet.

> _LinkedHashSet_: O LinkedHashSet é uma implementação da interface Set que mantém a ordem de inserção dos elementos, além de usar uma tabela hash para obter um bom desempenho de busca. Ele é semelhante ao HashSet, mas também mantém uma lista duplamente vinculada que preserva a ordem de inserção. Isso permite que os elementos sejam percorridos na ordem em que foram adicionados. O LinkedHashSet é útil quando você precisa manter a ordem de inserção dos elementos e também ter um bom desempenho de busca.




___
# References
[📝 Camila Instrutora DIO](https://github.com/cami-la/collections-java-api-2023/tree/master/src/main/java/list#arraylist-o-arraylist-%C3%A9-uma-implementa%C3%A7%C3%A3o-da-interface-list-que-armazena-os-elementos-em-uma-estrutura-de-array-redimension%C3%A1vel-isso-significa-que-ele-pode-crescer-automaticamente-%C3%A0-medida-que-novos-elementos-s%C3%A3o-adicionados-a-principal-vantagem-do-arraylist-%C3%A9-o-acesso-r%C3%A1pido-aos-elementos-por-meio-de-%C3%ADndices-o-que-permite-recuperar-um-elemento-espec%C3%ADfico-de-forma-eficiente-no-entanto-adicionar-ou-remover-elementos-no-meio-da-lista-pode-ser-mais-lento-pois-requer-a-realoca%C3%A7%C3%A3o-de-elementos)