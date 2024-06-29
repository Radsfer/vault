Status: #study 
Tags:
[[CEFET]], [[EDO]]

### Acontecimentos da aula
- Apresentações.
- Revisão de conceitos básicos.
### Matéria
- **EDO** -> Equação onde a incógnita é uma derivada ordinária (somente uma).

### Exemplos
### 2ª Lei de Newton
#### EDO 1ª ordem
$$ \vec{F} = m . \frac {d\vec{v}}{dt} \tag{1}$$
#### EDO 2ª ordem
$$\vec{F} = m . \frac {d^{2}s}{dt^{2}}\tag{2}$$
### Outros exemplos
$$ y'+y=0 \tag{1}$$
$$\frac {dy}{dx}=x^{2} \tag{2}$$
$$y"-4y'+3y=0 \tag{3}$$
$$ \frac {d^{2}y}{dx^{2}}-4\frac{dy}{dx} +3y=0 \tag{4}$$

Se:$$\begin{cases}y_{1=}cos x\\y_2= sen x \end{cases}$$ Verifique se: 
$$y''+y'=0$$

$$ y_2''+y_2'=-\cos {x} +cos{x}=0  \tag{1}$$
Ou
$$y_2''+y_2=-\sin {x} +\sin {x}=0 \tag{2}$$
### Observação

Essas soluções não são únicas, elas são chamadas de *soluções particulares* e a solução para 
$$y=c_1\cos x+c_2\sin x $$com c<font size=0.05>1</font> e c<font size=0.05>2</font> <a>&#8712</a>|R  é a solução geral.
para y<font size=0.05>1</font>=cos x, tem-se c<font size=0.05>1</font>=1 e c<font size=0.05>2</font>=0
### Classificação
- **TIPO**
*Ordinária* - Apresenta variável Ex.: y'=sen x
*Parcial* - apresenta mais de uma variável
Ex.: $$ \frac {d^{2}y}{dx^{2}}-4\frac{dy}{dt} =0$$
com y=f<font size=0.05>(x,t)</font>
*Ordem* é a ordem da derivada mais alta
1ª ordem y'+y=0
2ªordem y"+4y'+3y=0
etc.

## Exercícios

#### Equações Diferencias Separáveis
São EDO de 1ª ordem em que separar
os membros:
$$\frac{dy}{dx}$$
### Exemplos
##### (Q1)

$$y'=\frac {x^{2}}y \tag{1}$$
$$\frac {dy}{dx}=\frac {x^{2}}y \tag{2}$$
$$ydy=x^{2}dx\tag{3}$$
$$\int ydy=\int x^2dx\tag{4}$$
$$\frac {y^{2}}2=\frac {x^3}3+C\tag{5}$$
$$y^{2}= \frac{2x^3}3+C\tag{6}$$
\ **Solução Geral**:
$$y=+-\sqrt{\frac{2x^3}3+C}\tag{7}$$ 

##### (Q2)  
$$\frac{dy}{dx}=\frac{e^x}y\tag{1}$$
$$ydy=e^xdx\tag{2}$$
$$\int {ydy}=\int{e^x dx}\tag{3}$$
$$\frac{y^2}2=e^x+C\tag{4}$$
$$y^2=2e^x+C\tag{5}$$
$$y=\sqrt{2e^x+C}\tag{6}$$

##### (Q3)
$$y'=\frac{x}{e^y}\tag{1}$$
$$\frac{dy}{dx}=\frac{x}{e^y}\tag{2}$$
$$e^ydy=xdx\tag{3}$$
$$\int{e^y dy}=\int{x dx}\tag{4}$$
$$e^y=\frac{x^2}2 +C\tag{5}$$
$$ln (e^y)=ln(\frac{x^2}2+C)\tag{6}$$
$$y=ln(\frac{x^2}2+C)\tag{7}$$

##### (Q4) 
$$y=ln(\frac{x^2}2+C)\tag{1}$$
$$\frac{dy}{dx}=\frac{x+1}{e^{2y}}\tag{2}$$
$$e^{2y} dy= x+1dx\tag{3}$$
$$\int{e^{2y} dy}=\int{x+1 dx}\tag{4}$$
$$\frac{1}{2} e^{2y}=\frac{x^2}2 +x+C\tag{5}$$
$$e^{2y}=x^2+2x+C\tag{6}$$
$$ln (e^{2y})=ln(x^2+2x+C)\tag{7}$$
$$y \frac{1}{2}=ln(x^2+2x+C)\tag{8}$$
$$y=\frac{1}2 ln(x^2+2x+C)\tag{9}$$
$$y=ln((x^2+2x+C)^\frac{1}2)\tag{10}$$
$$y=ln(\sqrt{x^2+2x+C})\tag{11}$$

### Contato professora
##### (35) 99114-0408
arianafruhauf@yahoo.com

### Distribuição de  Pontos

| Avaliações | Valor |   Datas |
| ---------- | ----: | ------: |
| 1ª Prova   |  30,0 |   11/04 |
| 2ª Prova   |  30,0 |   23/05 |
| 3ª Prova   |  30,0 |   27/06 |
| Atividades |  10,0 | ------- |
### Livro
 (Cálculo volume 2 - Howard Anton, Irl Bivens, Stephen Davis.)
- [Calculo_V2.pdf]
