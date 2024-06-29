Status: #study 
Tags:
[[CEFET]], [[AOC]]
### Relembrando
 - Ciclo de instrução visto na [[AOC 3ª - Aula]]


### Ciclo de operação
![[pipe_line_Instruction_SandParalel.png]]
*p.51*

#### Da errado quando
- Uma instrução depende da outra. (Execução de instrução por prioridade).
- Quando existe a necessidade de uma variável fora da memória [[AOC - Cache]].
### Paralelismo
![[Mult_CPU.png]]
*p.56*
### <u>Cluster</u>
```mermaid
graph LR;

PC1(Computer 1)<-->PC2(Computer 2)
PC2<-->PC3(Computer 3)
PC3<-->PC4(Computer 4)
PC4<-->PC1

linkStyle 0 stroke:red;
linkStyle 1 stroke:red;
linkStyle 2 stroke:red;
linkStyle 3 stroke:red;
```

> <font color="red">RACE</font>
