# 微积分

- $\displaystyle \lim _{\Delta x \rightarrow 0} \frac{f\left(x_{0}+\Delta x\right)-f\left(x_{0}\right)}{\Delta x}=f^{\prime}\left(x_{0}\right) = 切线的斜率$

## 常见函数的导数

### 代数，指数和对数函数的导数

$c^\prime=0 \\
\left(x^{n}\right)^{\prime}=nx^{n-1} \quad (n 为自然数) \\
\left(x^{\mu}\right)^{\prime}=\mu x^{\mu-1} \quad (x>0，\mu \neq 0) \\
\left(e^x\right)^{\prime}=e^x \\
\left(a^x\right)^\prime=a^x\ln a \\
\left(\log_a{x}\right)^\prime=\frac{1}{x\ln a} \quad \left(a>0,a\neq 1,x>0\right) \\
\left(\ln{x}\right)^\prime=\frac{1}{x} \\
\left(x^x\right)^\prime=x^x\left(1+\ln x\right) \\
$

### 三角函数的导数

$
\left(\sin x\right)^\prime=\cos x \\
\left(\cos x\right)^\prime=-\sin x \\
\left(\tan x\right)^\prime=\sec^2 x \\
\left(\cot x\right)^\prime=-\csc^2 x \\
\left(\sec x\right)^\prime=\sec x\tan x \\
\left(\csc x\right)^\prime=-\csc x\cot x \\
$

### 反三角函数的导数

$\begin{aligned}
(\arcsin x)^{\prime} &=\frac{1}{\sqrt{1-x^{2}}}(|x|<1) \\
(\arccos x)^{\prime} &=-\frac{1}{\sqrt{1-x^{2}}}(|x|<1) \\
(\arctan x)^{\prime} &=\frac{1}{1+x^{2}} \\
(\operatorname{arccot} x)^{\prime} &=-\frac{1}{1+x^{2}} \\
(\operatorname{arcsec} x)^{\prime}&=\frac{1}{|x| \sqrt{x^{2}-1}}(|x|>1) \\
(\operatorname{arccsc} x)^{\prime}&=-\frac{1}{|x| \sqrt{x^{2}-1}}(|x|>1) \\
\end{aligned}
$

### 双曲函数的导数

$\begin{array}{ll}
(\sinh x)^{\prime}=\cosh x=\frac{e^{x}+e^{-x}}{2} & (\operatorname{arsinh} x)^{\prime}=\frac{1}{\sqrt{x^{2}+1}} \\
(\cosh x)^{\prime}=\sinh x=\frac{e^{x}-e^{-x}}{2} & (\operatorname{arcosh} x)^{\prime}=\frac{1}{\sqrt{x^{2}-1}}(x>1) \\
(\tanh x)^{\prime}=\operatorname{sech}^{2} x & (\operatorname{artanh} x)^{\prime}=\frac{1}{1-x^{2}}(|x|<1) \\
(\operatorname{sech} x)^{\prime}=-\tanh x \operatorname{sech} x & (\operatorname{arsech} x)^{\prime}=-\frac{1}{x \sqrt{1-x^{2}}}(0<x<1) \\
(\operatorname{csch} x)^{\prime}=-\operatorname{coth} x \operatorname{csch} x(x \neq 0) & (\operatorname{arcech} x)^{\prime}=-\frac{1}{x \sqrt{1-x^{2}}}(0<x<1) \\
(\operatorname{coth} x)^{\prime}=-\operatorname{csch}^{2} x(x \neq 0) & (\operatorname{arcoth} x)^{\prime}=\frac{1}{1-x^{2}}(|x|>1)
\end{array}$

## 一般求导法则

### 线性法则

$[M f(x)]^{\prime}=M f^{\prime}(x) \\
(u \pm v)^\prime =u^\prime \pm v^\prime$

### 乘法法则

$(uv)^\prime =u^\prime v + v^\prime u$

### 除法法则

$(\frac{u}{v})^\prime = \frac{u^\prime v - v^\prime u}{v^2} \quad(v \neq 0)$

### 倒数法则

$(\frac{1}{v})^\prime=\frac{-v^\prime}{v^{2}} \quad(v \neq 0)$

### 复合函数求导法则

$\begin{array}{l}
(f \circ g)^{\prime}=\left(f^{\prime} \circ g\right) g^{\prime} \\
\frac{\mathrm{d} f[g(x)]}{\mathrm{d} x}=\frac{\mathrm{d} f(g)}{\mathrm{d} g} \frac{\mathrm{d} g}{\mathrm{d} x}=f^{\prime}[g(x)] g^{\prime}(x)
\end{array}$

### 反函数的导数

$\frac{\mathrm{d} f}{\mathrm{d} x}=\frac{1}{\frac{\mathrm{d} g(f)}{\mathrm{d} f}}=\left[\frac{\mathrm{d} g(f)}{\mathrm{d} f}\right]^{-1}=\left[g^{\prime}(f)\right]^{-1}$

$\begin{aligned}
\quad & 证明： \\
&\because g(f(x))=x, \text { 故 } g(f(x))^{\prime}=1, \text { 根据复合函数求导法则 } \\
& g(f(x))^{\prime}=\frac{\mathrm{d} g[f(x)]}{\mathrm{d} x}=\frac{\mathrm{d} g(f)}{\mathrm{d} f} \frac{\mathrm{d} f}{\mathrm{d} x}=1\\
&\therefore \frac{\mathrm{d} f}{\mathrm{d} x}=\frac{1}{\frac{\mathrm{d} g(f)}{\mathrm{d} f}}=\left[\frac{\mathrm{d} g(f)}{\mathrm{d} f}\right]^{-1}=\left[g^{\prime}(f)\right]^{-1}\\
&同理 \frac{\mathrm{d} g}{\mathrm{d} x}=\frac{1}{\frac{\mathrm{d} f(g)}{\mathrm{d} g}}=\left[\frac{\mathrm{d} f(g)}{\mathrm{d} g}\right]^{-1}=\left[f^{\prime}(g)\right]^{-1}
\end{aligned}$