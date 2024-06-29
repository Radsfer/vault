Status: #study 
Tags:
[[CEFET]], [[AOC]]
## Memória
![[exemplo_Memoria_esquema.png]]

![[memory_8_16.png]]
 <b>(a)</b> 12x8 ->(0->11 | | 0000->1011)
 <b>(b)</b> 8x12->(0->8 | | 000->111)
 <b>(c)</b> 6x16->(0->6 | | 000->101)
##### Caso interessante
> Quando um aparelho aceita um pendrive de até 2GB por conta do endereçamento
$$\begin{cases}1GB=2^{30}\\2GB=2^{31{(Bits\ de\ endereçamento)}}\\4GB=2^{32}\end{cases}$$
### Endereçamento
![[memoria_de_bit_a_bit.png]]
> O paralelismo nesse caso ajuda na velocidade, afinal usando um endereçamento de 1 bit e lendo bit a bit então quando comparado, o uso de palavras de bit maior pode-se conseguir ler um maior número  dados em relação aos tamanhos menores.
### Hierarquia
![[hierarquia_memoria.png]]
### Organização
![[estrutura_logica_simples.png]]
>**Observação: Tudo conectado em um barramento controlado pela CPU.**

### Exemplo endereçamento binário
![[tabela_ascii.png]]