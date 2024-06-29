
Status: #study 
Tags:
[[CEFET]], [[AOC]]
<h3> Literatura recomendada </h3>
- Andrew Tanembaum (5ª/6ª)
>Computadores são máquinas de calcular eletrônicas digitais capazes de executar um programa fornecido pelo o usuário
### História dos computadores digitais
+ Com os primeiros computadores era necessário aprender a linguagem de máquina 
- Principais financiadores no começo: 
	1. Forças Armadas.
	2. Banco.
	3. Agronegócio (Meteorologia).
	4. Aeroporto.

| Maquina     | Tipo     | Linguagem | Exemplo       |
| ----------- | -------- | --------- | ------------- |
| M0          | Hardware | L0        | 001,101,110   |
| M1(Virtual) | ISA      | L1        | ADD, SUB, INC |

> **Instruction Set Archiquerture**
#### Características Importantes dos processadores
 - Consumo energético
 - Tamanho
 - Calor
 - Velocidade
#Eficiencia
### CISC X RISC
#### CISC
- Complex
- Instruction
- Set
- Computer
#### RISC
- Reduced
- Instruction
- Set
- Computer

| Maquina      | Tipo              | Linguagem | Exemplo       | Função        |
| ------------ | ----------------- | --------- | ------------- | ------------- |
| M0           | Hardware          | L0        | 001,101,110   | Calculo       |
| M1(Virtual)  | Micro Arquitetura | L1        |               | Interpretação |
| M2 (Virtual) | ISA               | L2        | ADD, SUB, INC | Tradução      |
> **Interpretador recebe uma instrução por vez**

##### Ex.:
L2 ->MULT 3x4 -> L1 -> ADD 4+4+4 ->L0 01010101010.^[O binário não significa nada em especifico só exemplo mesmo]


