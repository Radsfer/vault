Status: #study 
Tags:
[[CEFET]], [[EDO]]

###### Exemplo 2
$$\frac{dy}{dx}-y=e^{2x}\tag{0}$$
$$\begin{cases}p(x)=-1\\q(x)=e^{2x}\end{cases}$$

$$μ(x)=e^{\int{-1dx}}\tag{1}$$
$$μ(x)=e^{-x}\tag{2}$$
$$y=\frac{1}{μ(x)}\int{μ(x)q(x)dx}\tag{3}$$
$$y=\frac{1}{e^{-x}}\int{e^{-x}*e^{2x}dx}\tag{4}$$
$$y=e^{x}\int{e^{x}dx}\tag{5}$$
$$y=e^{2x}+C\tag{6}$$

###### Exemplo 3
$$x\frac{dy}{dx}-y=x,\ com\ y(1)=2$$

$$\frac{dy}{dx}-\frac{y}{x}=1\tag{1}$$
$$\begin{cases}p(x)=-\frac{1}{x} \\ q(x)=1\end{cases}$$
> p(x) é contínua em (-infinity,0)União(0,+infinity)
> q(x) é contínua em (-infinity,+infinity)

<b><u>p(x) contínua em (0,+infinity)</u></b>
$$μ(x)=e^{\int{-\frac{1}{x}dx}}\tag{2}$$
$$μ(x)=e^{-ln|x|}=>μ(x)=e^{\frac{1}{lnx}}=>\frac{1}{x}\tag{3}$$
$$y=\frac{1}{\frac{1}{x}}\int{\frac{1}{x}(1)dx}\tag{4}$$
<b><u>Soluação Geral:</u></b>
$$y=xln(x)+xC\tag{5}$$ 
<u>PVI</u>
$$2=1ln1+1C\tag{6}$$
$$2=0+C\tag{7}$$
$$C=2\tag{8}$$
<b><u>Solução Particular</u></b>
$$y=xln(x)+2x\tag{9}$$

### Exercícios para 4ªFeira <u>(27/03)</u>
<b><u>Secção 9.1</u></b>
**pag.593** :(7,9,11,13,25,27,41)
