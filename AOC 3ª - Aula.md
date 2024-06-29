Status: #study 
Tags:
[[CEFET]], [[AOC]]
## Esquema de arquitetura de Von Neumann
![[ArquiteruraVonNeumann.png]]
### Tipos de instrução
1. Operações matemáticas( ADD, SUB , INC, OR, AND, ...)
2. Desvios no programa ( GoTo, Call, IF, FOR, ...) 
3. Acesso a memória (STORE, LOAD, READ, WRITE, ...)
4. NOP (no operation)
5. HALT (comando para manter o loop de operação até o final da instrução)
### Ciclo de operação
1. Busca de instrução
2. Incremento do Program Counter (ponteiro do programa)
3. Determinar o tipo de instrução
4. Determinar o enderenço do dado a ser utilizado
5. Busca do dado na memória
6. Execução
7. Retorna a (1)

### Interpretador
![[InterpretadoSimplesJava.png]]