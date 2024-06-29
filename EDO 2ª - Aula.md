Status: #study 
Tags:
[[CEFET]], [[EDO]]
### PVI Problemas de Valor Inicial
- procurar q5


##### Q6
$$y'=xy$$
$$y_{(0)}=2$$

**Logo**
$$\frac{dy}{dx}=xy\tag{1}$$

$$\frac{1}{y dy} = xdx\tag{2}$$
$$\int{\frac{1}{y dy}}=\int{x dx}\tag{3}$$

$$ln|y|=\frac{x^2}2+C\tag{4}$$

$$e^{ln|y|}=e^{\frac{x^{2}}{2} + C}\tag{5}$$
$$|y|=e^{\frac{x^2}{2}}e^{C}\tag{6}$$
$$|y|=C.e^{\frac{x^2}{2}}\tag{7}$$

$$y= \phantom{-}^+\!\!\!\!{-} C.e^{\frac{x^2}{2}}\tag{8}$$
$$y= C.e^{\frac{x^2}{2}}\tag{Geral}$$

###### PVI 
x=0 & y=2
y= C.e^{x^2/2}
2=Ce^{0^2/2}
C=2
y=2e^{x^2/2}(Particular)

##### Q7
$$
\begin{cases} \frac{dy}{dx}=-4xy^2\\  y_{(0)}=1 \end{cases}\tag{Dados}$$
$$y^{-2}dy={-4x} dx\tag{1}$$
$$\int{y^{-2}dy}=-4\int{xdx}\tag{2}
$$
$$-(\frac{y^{-1}}{1})=\frac{-4x^{2}}2\tag{3}$$
**Solução Geral:**
$$y=\frac{1}{2x^{2}-C}\tag{4}$$

###### PVI
Para:
$$\begin{cases}x=0 \\y=1 \end{cases}$$
Temos:
$$y=\frac{1}{2x^{2}-C}\tag{1}$$

$$1=\frac{1}{0^{2}-C}\tag{2}$$

$$1=\frac{1}{-C}\tag{3}$$
$$C=-1\tag{4}$$
**Solução Particular:**
$$y=\frac{1}{2x^{2}+1}$$

##### Q8
$$\begin{cases} \frac{dy}{dx}=\frac{2x-1}{3y^{2}-3}\\y_{(1)}=0 \end{cases}$$
$$\int{3y^{2}-3}dy=\int{2x-1dx}\tag{1}$$
$$\frac{3y^3}{3} - 3y= \frac{2x^{2}}2-x+C\tag{2}$$
**Solução Geral Implícita:**
$$\frac{3y^3}3 - 3y= x^{2}-x+C\tag{3}$$
###### PVI
$$\begin{cases}x=1\\y=0\end{cases}$$
$$\frac{3*0^3}3 - 3*0= 1^{2}-1+C\tag{1}$$
$$C=0\tag{2}$$
**Solução particular Implícita**
$$\frac{3y^3}3 - 3y= x^{2}-x $$

##### Q9
$$\begin{cases} {4y-\cos{y}}\frac{dy}{dx}-3x^{2}=0\\y_{(0)}=0 \end{cases}$$
$$(4y-cosy)dy=3x^{2}dx\tag{1}$$
$$\int{(4y-cosy)dy}=\int{3x^{2}dx}$$
**Solução Geral Implícita**
$$2y^{2}-\sin{y}=x^{3}+C$$

###### PVI
$$2*0^{2}-\sin{0}=0^{3}+C\tag{1}$$
$$C=0\tag{2}$$
**Solução particular implícita**
$$2y^{2}-\sin{y}=x^{3} $$

##### Q10

Encontre uma curva no plano xy que passe por (0,3) e cuja reta tangente em um ponto (x,y) tenha inclinação {2x}/y
$$\begin{cases}\frac{dy}{dx}=\frac{2x}{y^{2}}\\y_{(0)}=3 \end{cases}$$


$$\int{y^{2}dy}=\int{2xdx}\tag{1}$$
$$\frac{y^{3}}3=x^{2}+C\tag{2}$$
**Solução Gera:**
$$y=\sqrt[3]{3x^{2}+3C}$$
###### PVI
$$\begin{cases}y=3\\x=0\end{cases}$$
$$3=\sqrt[3]{3*0^{2}+3C}\tag{1}$$
$$3^3={(\sqrt[3]{3*0^{2}+3C})}^3\tag{2}$$
$$27=3C\tag{3}$$
$$C=9\tag{4}$$
**Solução Particular**
$$y=\sqrt[3]{3x^{2}+27}$$

##### Q11
Considerando uma barra de cobre mergulhada em um recipiente com água mantida a temperatura de 20ºC e a temperatura da barra em um tempo(t) é satisfeita pela EDO=>y'=k(20-y) onde 0.5 e y(0)=400ºC. Determine a função y(t)
$$\begin{cases}y'=k(20-y)\\y_{(0)}=400 \end{cases}$$
$$\frac{dy}{dt}=0.5(20-y)\tag{1}$$


$$\int{\frac{1}{20-y} dy}=\int{0.5dt}\tag{2}$$
$$u=20-(1)y\tag{3}$$
**Subistituição:**
$$\frac{du}{dy}=-1\tag{4}$$
$$du=-dy\tag{5}$$
$$dy=-du\tag{6}$$
$$\int{{1}{u}(-du)}\tag{7}$$
$$\int{\frac{-1}{u} du}=-\int{\frac{1}{u} du} =-ln|u|\tag{8}$$
**Voltando:**
$$-ln|20-y|=0.5t+C\tag{9}$$
$$e^{20-y}=e^{-0.5t-C}\tag{10}$$
$$20-y=+-{e^{-0.5t}e^{-C}}\tag{11}$$
$$(-1)20-y=(-1)C.e^{-0.5t}\tag{12}$$
$$y=20-C.e^{-0.5t}\tag{13}$$
###### PVI
$$\begin{cases}t=0 \\y=400ºC \end{cases}$$
$$400=20-C.e^{-0.5 * 0}\tag{14}$$
$$C=-380\tag{15}$$
**Solução particular:**
$$.:y=20-380e^{-0.5t}$$
### Pra próxima semana
*secção 9.1
 (p.592&593)*
 - Exercícios:
	 >1,3,15,17,21,29 e 31 
