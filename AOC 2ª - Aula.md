Status: #study 
Tags:
[[CEFET]], [[AOC]]
## Diagrama de máquina de 1ª Geração

```mermaid
graph TB;


UC-->|ADDR1<br>ADDR2<br>ADDR3|MD;
ULA<==>|Data|MD[(MD)]; 
PM(PM)-->UC; 

subgraph CPU;
UC(UC)-->|0010|ULA(ULA)
ULA(ULA)-->|N<br>Z|UC(UC)
end

style CPU fill:lightblue,stroke:#333,stroke-width:4px,stroke-dasharray: 3 3;
linkStyle 2 stroke:blue;
```
> PM = Memória de Programa
> UC = Unidade de controle
> ULA = Unidade de Lógica e Aritmética
> DM = Memória de dados

## Ciclo de máquina
1. Busca da instrução
2. Decodificação
3. Execução
#Eficiencia 

## Software Básico (ISA)
1. Operações Matemáticas
2. Desvios (Go to,if,...)
3. Acesso à memória (load, store, read, write)

*Como visto na [[AOC 1ª - Aula]] é aqui onde aparece as principais diferenças entre RISC X CISC.*

## Diagrama da unidade de Controle

```mermaid
graph LR;

PC-->|ADRESS|PM(PM);
PM(PM)-->|INSTRUCTION|IR
subgraph UC
	Clk-->PC(Program Controler)
	IR(Intruction Register)
end

style UC fill:lightblue,stroke:#333,stroke-width:4px,stroke-dasharray: 3 3;

linkStyle 1 stroke:blue;
linkStyle 0 stroke:blue;
```
