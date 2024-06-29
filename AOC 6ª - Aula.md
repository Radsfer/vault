Status: #study 
Tags:
[[CEFET]], [[AOC]]
### Relembrando
- Na [[AOC 5ª - Aula]] quando vemos a organização em barramento existem também a organização em estrela e rede (olhar depois).
### Barramento dados:
![[barramento_Exemplo.png]]
##### Qual o periférico que usa mais dados?
- O monitor! Por exemplo quando vamos analisar a resolução 4k:
$$3840x2160\tag{60Hz}$$
$$\begin{cases} pixel= Red+Blue+Green\\pixel= 8bit+8bit+8bit\\pixel= (0-255)bit+(0-255)bit+(0-255)bit\\24bit=16M\ colors\end{cases}$$
$$Tx=(3840\ . \ 2160)\frac{pixel}{frame} \ . \ 24\frac{bits}{pixel} \ . \ 60\frac{frames}{s} $$
$$Tx=1,2\ .\ 10^{10} \frac{bits}{s}= 12 \frac{GB}{s}$$
<font size=20 color="red">12 GIGA <u>bytes</u> por segundo</font>
##### Então como vemos vídeos nessa resolução?
- Fraunhofer protocolo <u>M</u> PEG (<b><u>bps</u></b>).
> Então os algoritmos de decodificação/compressão são os responsáveis pela possibilidade do envio de vídeos/audios/imagens de grandes resoluções/qualidade pela internet. (Palavra chave é CODEC)
#### Evolução da internet

| ano  | velocidade    | tipo        |
| ---- | ------------- | ----------- |
| 1993 | 56kbps        | modem       |
| 2003 | 1Mbps         | velox(ADSL) |
| 2013 | 100Mbps       | 4G          |
| 2023 | 1Gbps(10/100) | O.F.        |
### Concluindo
- Mesmo nos dias atuais ainda existe gargalo de dados. Por isso existe a discussão entre computadores de tempo real (latência em um range garantido).