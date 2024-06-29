202405191654
Status: #study 
Tags:
 [[Java]], [[bootCampSantander]], [[Coding]].
# Java Collections - Generic Types

- Um tipo genérico é uma **classe** genérica ou uma **interface** que é parametrizada em relação a tipos.
- A **classe** `Box` vai ser alterada para servir de exemplo
``` Java
public class Box {
    private Object object;

    public void set(Object object) { this.object = object; }
    public Object get() { return object; }
}
```
- O símbolo `< >` é chamado de _diamond_ ou _diamond operator_ foi um recurso adicionado no Java 7 e é usado no contexto de tipos genéricos em Java para inferir automaticamente o tipo com base no contexto.
- Para atualizar a classe `Box` para usar generics, você cria uma declaração de tipo genérico alterando o código `public class Box` para `public class Box<T>`.
- Isso introduz a variável tipo, `<T>` que pode ser usada em qualquer lugar dentro da classe.
```Java
/**
Versão genérica da classe Box.
@param <T> o tipo do valor sendo armazenado
*/
public class Box<T> {
 // T representa "Type" (tipo)
    private T t;

    public void set(T t) { this.t = t; }
    public T get() { return t; }
}
```
- Como pode-se ver, todas as ocorrências de `Object` são substituídas por `T`. Uma variável de tipo pode ser qualquer tipo não primitivo que você especificar. Seja de **classe**, **interface**, **array** ou mesmo **variável de tipo**.
- Essa mesma técnica pode ser aplicada para criar interfaces genéricas.
- Os nome de parâmetro de um tipo mais comumente usados são:
	1. E - Elemento (usado extensivamente pelo **Java Collections Framework**)
	2. K - _key_ (chave)
	3. N - _number_ (número)
	4. T - _type_ (tipo)
	5. V - _value_ (valor)
	6. S, U, V, etc. - 2º, 3º, 4º tipos
## Vantages simples de usar generics nas interfaces Collection em Java
- **Segurança do tipo de dados** : O uso do _generics_ garante que apenas o objetos de um tipo específico possam ser adicionados à coleção, evitando erros de tipo e garantindo que você esteja lidando com os dados corretos.
- **Código mais legível**: Ao usar _generics_, você pode especificar o tipo de dado esperado ou retornado pela coleção, tornando código mais legível.
- **Detecta erros mais cedo**: O compilador verifica se você está usando os tipos corretos durante  a compilação, ajudando a identificar erros de tipo antes mesmo de executar o programa.
- **Reutilização de código**: Com o _generics_, você pode criar classes e métodos genéricos funcionam com tipos diferentes de coleções, evitando a necessidade de duplicar código para cada tipo específico.
- **Melhor desempenho**: O uso de _generics_, pode melhorar o desempenho , pois evita a necessidade de conversões de tipo desnecessárias e permite que o compilador otimize o código com base no tipo especificado.

___
# References
- [Java Tutorials - Generics - Generic Types.](https://docs.oracle.com/javase/tutorial/java/generics/types.html.)
