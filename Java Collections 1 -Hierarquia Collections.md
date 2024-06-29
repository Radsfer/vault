202405191639
Status: #study 
Tags:
 [[Java]], [[bootCampSantander]], [[Coding]].
# Java - Hierarquia Collections
- Uma coleção  (collection) é uma estrutura de dados que serve para agrupar muitos elementos em uma única unidade, estes elementos precisão ser `Objetos`.
- Uma `Collection` pode ter coleções homogêneas e heterogêneas, normalmente utilizamos coleções homogêneas de um tipo específico.
- O núcleo principal das coleções é formado pelas **interfaces** da figura abaixo, essas **interfaces** permitem manipular a coleção independente do nível de detalhe que elas representam. Temos quatro grandes tipos de coleções : `List` (lista), `Set` (conjunto), `Queue` (fila) e `Map` (mapa), a partir dessas **interfaces**, temos muitas subclasses concretas que implementam varias formas diferentes de se trabalhar com cada coleção.
 ![Hierarquia Java](https://raw.githubusercontent.com/cami-la/collections-java-api-2023/master/assets/image/collection-framework.png)
 - Todas as **interfaces** e classes são encontradas dentro do`package` (pacote) `java.util`.
 - Embora a **interface** `Map` não ser filha direta da **interface** `Collection` ela também é considera uma coleção devido a sua função.

___
# References
- [Universidade Java - Java Collections](http://www.universidadejava.com.br/java/java-collection/)
- [Oracle - Java™ Platform, Standard Edition 17 API Specification - Interface Collection](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html)
- ["Collections in Java Tutorial." DigitalOcean Community. ](https://www.digitalocean.com/community/tutorials/collections-in-java-tutorial](https://www.digitalocean.com/community/tutorials/collections-in-java-tutorial)
