Status: #study 
Tags:
[[CEFET]], [[EDO]]
### Classificação de equações diferenciais

#### <u>Tipo</u>
Ordinárias ou parciais
#### <u>Ordem</u>
1ª,2ª,3ª ordem etc.
#### <u>Linearidade</u>
Linear ou não linear.

Uma EDO é dita <u>linear</u> de ordem n quando pode ser escrita como
$$a_n(x)\frac{d^ny}{dx^n}+...a_2(x)\frac{d^2y}{dx^2}+a_1(x)\frac{dy}{dx}+a_0(x)=g(x)$$
em que a0,a1,a2,..,an e g são funções somente de x
##### <u>Observações</u>
- a variável y e todas as sua derivadas são do 1ºgrau.
- cada coeficiente depende unicamente da variável independente x ou são constantes

<u><b>Exemplo:</b></u> Classifique as EDOs em linear ou não linear e dê a ordem da equação.

###### Q1
(1-x)y''-4xy'+5y=cosx
linear de 2ª ordem
###### Q2
x{d^3y}/{dx^3}-2{{dy}{dx}}^4+y=0
não linear de 3ª ordem

###### Q3
yy'+2y=1+x^2
não linear de primeira ordem
###### Q4
x^2dy+(y-xy-xe^x)dx=0(%dx)
x^2{dy}/{dx}+(1-x)y-xe^x=0
x^2{dy}/{dx}+(1-x)y=xe^x
linear de primeira ordem
###### Q5
$$x^3y^{(4)}-x^{2}y''+4xy'-3y=0$$

linear de quarta ordem (não precisa aparentar todas em sequência nesse caso imagina-se como se y'''=0 )
###### Q6
$$\frac{d^{2}y}{dx^2}+9y=sin{y}$$
{d^{2}y}/{dx^2}+9y=sin{y}
não linear de segunda ordem(função seno dependendo de y)
###### Q7
{dy}/{dx}=sqrt{1+{{d^2y}/{dx^2}}^3}
não linear de segunda ordem (tem que ser obrigatoriamente de 1º grau!)
###### Q8
{d^2r}/{dt^2}=-K/r^2
não linear de 2ª ordem e não parcial(k e r^2)
###### Q9
{sin{x}}y'''-{cos{x}}y'=2
linear de terceira ordem(mesmo caso da Q5)
###### Q10
(1-y^2)dx+xdy=0(%dx)
1-y^2+x{dy}/{dx}=0
x{dy}/{dx}-y^2=-1
não linear de primeira ordem (y^2)
### Logo:
<a>
><b><u>O linear tem que ser na/ variável dependente no caso y a variável independente pode ser de qualquer grau</u></b> 
</a>
### Método de solução para EDOs de 1ª ordem
Uma EDO <u>linear</u> de 1ª ordem pode ser escrita como
$$\frac{dy}{dx}+p(x)y=q(x)$$
em que p e q são funções <u>contínuas</u> em um dado intervalo.

<b><u>Exemplos:</u></b>

$$\frac{dy}{dx}+x^2y=e^x\tag{1ª}$$
$$\begin{cases}p(x)=x^{2}\\ q(x)=e^x\end{cases}$$
$$y'+\sin{x}y+x^3=0\tag{2ª}$$
$$y'+\sin{(x)}\ y=-x^3$$
$$\begin{cases}p(x)=\sin{x}\\q(x)=-x^3\end{cases}$$
#### <u>Método do fator integrante</u>
Esse método, desenvolvido por Leibniz, consiste na <u>multiplicação</u> da EDO por uma função μ(x) que será escolhida de modo que a equação resultante seja <u>facilmente integrável</u>, logo a função μ(x) é denominada de <u>fator integrante</u>.
#### <u>Contrução do Método</u>
$$\frac{dy}{dx}+p(x)y=q(x)\tag{0}$$

<u>1º Multiplicar ambos os lados por μ(x)</u>
$$μ(x)\frac{dy}{dx}+μ(x)p(x)y=μ(x)q(x)\tag{1}$$
$$\frac{d{(μ(x)y)}}{dx}=μ(x)q(x)\tag{2}$$

<u>2º Aplicar Integral</u>
$$\int{\frac{d{(μ(x)y)}}{dx}}=\int{μ(x)q(x)dx}\tag{3}$$
$$μ(x)y=\int{μ(x)q(x)dx}\tag{4}$$
$$μ(x)=\frac{1}{y}\int{μ(x)q(x)dx}\tag{5}$$

<u>Definindo μ(x)</u>
$$\frac{d[μ(x)y]}{dx} = μ(x)\frac{dy}{dx}+μ(x)p(x)y\tag{6}$$
$$\frac{d[μ(x)]}{dx}*y+μ(x)\frac{dy}{dx}=μ(x)\frac{dy}{dx}+μ(x)p(x)y\tag{7}$$
$$\frac{d[μ(x)]}{dx}=μ(x)p(x)\tag{8}$$

$$\frac{1}{μ(x)}*\frac{d[μ(x)]}{dx}=p(x)\tag{9}$$
$$\frac{d[ln|μ(x)|]}{dx}=p(x)\tag{10}$$
$$\int{\frac{d[ln|μ(x)|]}{dx}}=\int{p(x)dx}\tag{11}$$
$$ln|μ(x)|=\int{p(x)dx}$$

<b><u>Fator Integrante:</u></b>
$$μ(x)=e^{\int{p(x)dx}}\tag{12}$$
