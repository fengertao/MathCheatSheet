# 高等数学复习笔记

本文只讲重要概念，过于简单的不再重复。

## 空间解析几何

### 向量

#### 模

向量的模$|(x,y,z)|=\sqrt{x^2 + y^2 + z^2} $

其几何意义为向量的长度

#### 点乘

$(x_1,y_1,z_1)\cdot(x_2,y_2,z_2)=x_1\times x_2 + y_1\times y_2 + z_1\times z_2 $

其几何意义为两个向量的模的乘积再乘以两向量夹角的余弦。也代表A向量在B向量的投影再乘以B向量。

其物理意义为A向量在B向量方向做的功。

#### 叉乘

$(x_1,y_1,z_1)\times(x_2,y_2,z_2)=\left[\begin{array}{ccc}
i & j & k \\
x_1 & y_1 & z_1 \\
x_2 & y_2 & z_2 \\
\end{array}\right] $

其几何意义为与两个向量都垂直的新向量，其方向符合右手螺旋法则，其长度为两向量围成的平行四边形的面积，即向量的模的积再乘以夹角正弦。

叉乘满足**反**交换律和分配律。

#### 混合积

$(x_1,y_1,z_1)\cdot[(x_2,y_2,z_2)\times(x_3,y_3,z_3)]=\left[\begin{array}{ccc}
x_1 & y_1 & z_1 \\
x_2 & y_2 & z_2 \\
x_3 & y_3 & z_3 \\
\end{array}\right] $

其几何意义为三个向量围成的六面体的体积，也是三棱锥体积的六倍。三向量共面。

### 平面

#### 平面一般表达式

$Ax+By+Cz+D=0$

其法向量为$ (A,B,C)$，也就是平面的垂线的方向

#### 点法式

$A(x-x_0)+B(y-y_0)+C(z-z_0)=0$

其中$(x_0,y_0,z_0)$是平面上任意一点

#### 截距式

$\frac{x}{a}+\frac{y}{b}+\frac{z}{c}=1$

其中$(a,0,0),(0,b,0),(0,0,c)$为平面在$x,y,z$轴的截距

#### 点和平面的距离

$d = \frac{|Ax_0+By_0+Cz_0+D|}{\sqrt{A^2+B^2+C^2}}$

### 直线

#### 直线标准表达式

$\left\{\begin{aligned}A_1x+B_1y+C_1z+D_1&=0\\A_2x+B_2y+C_2z+D_2&=0\end{aligned}\right.$

其几何意义为两个平面相交成为一条直线。

其方向和两平面的法向量都垂直，所以为$(A_1,B_1,C_1)\times(A_2,B_2,C_2)$。

#### 对称方程

$\frac{x-x_0}{m}=\frac{y-y_0}{n}=\frac{z-z_0}{p}$

$(m,n,p)$为直线的方向，都不能为0

#### 参数方程

$\left\{\begin{aligned}x&=x_0+mt\\y&=y_0+nt\\z&=z_0+pt\end{aligned}\right.$

#### 直线和平面垂直

直线的方向和平面法向量点乘为0

#### 直线和平面平行

直线的方向和平面法向量叉乘为0

#### 点和直线的距离

公式很复杂，一般不作为考点。

## 求极限

### 洛必达法则

$ \displaystyle 如果f(x)和g(x)在i处都趋近于0，\lim_{x \to i}f(x)/g(x)=\displaystyle \lim_{x \to i}f'(x)/g'(x)$

解读：因为两条曲线都趋近于0，靠近0点附近近似于两条直线，直线的斜率的比值就是直线上的点的y的比值。

### 夹逼定理

$ f(x) <= g(x) <= h(x)，且f(x)和h(x)收敛于y，那么g(x)也收敛于y。$

### 单调有限序列必有极限

夹逼定理的特例

### 罗尔定理

f(a)=f(b)，f在[a,b]间连续可导，则a,b间必有一点f'(c)=0

### 拉格朗日中值定理

就是把罗尔定理拉斜了。

### 柯西中值定理

就是[a,b]区间f(x),g(x)两个函数的导数的比值，至少有一点等于$\frac{f(b)-f(a)}{g(b)-g(a)}$

## 求导

### 基本公式
$(C)'=0\\
(x^n)'=nx^{n-1}\\
(\sin x)'=\cos x\\
(\cos x)'=\sin x\\
(e^x)'=e^x\\
(\ln x)'=\frac{1}{x}$

### 其它公式

$(a^x)'=\ln a\times a^x\\
(log_ax)'=\frac{1}{x\ln a}\\
(\tan x)'=sec^2 x\\
(\cot x)'=-\csc^2 x\\
(\sec x)'=\sec x\tan x\\
(\csc x)'=-\csc x\cot x\\
(\arcsin x)'=\frac{1}{\sqrt{1-x^2}}\\
(\arccos x)'=-\frac{1}{\sqrt{1-x^2}}\\
(\arctan x)'=\frac{1}{1+x^2}\\
(\arccot x)'=-\frac{1}{1+x^2}
$

### 运算法则

* $(u+v)'=u'+v'$
* $(uv)'=u'v+v'u$
* $(\frac{u}{v})'=\frac{u'v-v'u}{v^2}$
* $f[g(x)]'=f'[g(x)]g'(x)$
* $\frac{dx}{dy}=\frac{1}{\frac{dy}{dx}}$
  反函数的导数等于直接函数的倒数，但注意反函数的x是原函数的y
  例：求$(\arcsin x)'$
  $x=\sin (\arcsin x)\\
  两边求导 1=cos(\arcsin x)*(\arcsin x)'\\
  (\arcsin x)'=\frac{1}{cos(\arcsin x)}=\frac{1}{\sqrt{1-\sin^2(\arcsin x)}}=\frac{1}{\sqrt{1-x^2}}$
  也可以便捷运算：
  $(\sin x)'=\cos x\\
  (\arcsin x)'=\frac{1}{\cos y}=\frac{1}{cos(arcsinx)}=\frac{1}{\sqrt{1-x^2}}$

### 求导技巧

* y=f(x)求导，有时可以先ln(y)=ln(f(x))，两边求导后再消除y。例如：
  $y=x^x\\\ln y = x \ln x\\\frac{1}{y}y'=1+\ln x\\y'=y(1+lnx)\\y'=x^x+x^x\ln x$

### 泰勒级数

泰勒公式是用多项式逼近原函数，其思想为：如果两个数组在某$x_0$处值相同，一阶导数相同，二阶导数相同...N阶导数都相同，那么这两条曲线将十分拟合。

$f(x)=f(x_0)+f'(x_0)(x-x_0)+\frac{f''(x_0)}{2!}(x-x_0)^2+\cdots+\frac{f^{(n)}(x_0)}{n!}(x-x_0)^n+o(x^n)$

麦克劳林公式是泰勒公式当$x_0=0$的特殊情况

$f(x)=f(0)+f'(0)x+\frac{f''(0)}{2!}x^2+\cdots+\frac{f^{(n)}(0)}{n!}x^n+o(x^n)$

$e^x=1+x+\frac{1}{2!}x^2+\cdots+\frac{1}{n!}x^n+o(x^n)$

$\sin x=x-\frac{1}{3!}x^3+\frac{1}{5!}x^5-\cdots+o(x^n)$

$\cos x=1-\frac{1}{2!}x^2+\frac{1}{4!}x^4+\cdots+o(x^n)$

$e^{i\theta}=\cos \theta + i \sin \theta$

### 傅里叶级数

对于循环区间为$[-\pi, \pi]的周期函数，傅里叶级数是利用$$1, \sin x, \cos x, \sin 2x,\cos 2x,\cdots,\sin nx,\cos nx$相互之间的全正交性，将函数的时域变换为频域。

全正交：

* $\int_{-\pi}^{\pi}1 \times \sin kxdx=0$
* $\int_{-\pi}^{\pi}1 \times \cos kxdx=0$
* $\int_{-\pi}^{\pi}\sin jx\sin kxdx=0  \ \ \ (j \neq k)$
* $\int_{-\pi}^{\pi}\cos jx\cos kxdx=0  \ \ \ (j \neq k)$
* $\int_{-\pi}^{\pi}\sin jx\cos kxdx=0$

时域和频域可以相互转化，这样在工程上，可以先把数字信号转为频域，然后处理（比如降低频率女声转为男声），然后再重新转为时域信号。

$\displaystyle f(x)=\frac{a_0}{2}+\sum_{n=1}^{\infty}(a_n\cos nx+b_n\sin nx)\\
a_n=\frac{1}{\pi}\int_{-\pi}^{\pi}f(x)\cos nxdx   \ \ \ (n=0,1,2,3,\cdots)\\
b_n=\frac{1}{\pi}\int_{-\pi}^{\pi}f(x)\sin nxdx   \ \ \ (n=1,2,3,4,\cdots)$

* 对于同样的频率n，为什么既有$a_n\cos nx$，又有$b_n\sin nx$？原因是$\sqrt{a_n^2+b_n^2}$决定了该频率的强度，而两者之间的比例关系决定了该频率的相位。所以也可以表示为$\displaystyle f(x)=\frac{a_0}{2}+\sum_{n=1}^{\infty}a_n\sin (nx+\omega_n)$
* 如果f(x)在$[-\pi, \pi]之间只有有限个第一类间断点并且只有有限个极值点，那么其傅里叶级数在连续点收敛于f(x)，在第一类间断点收敛于左极限和右极限的平均值。

### 方向导数和梯度

如果$f(x,y)在(x_0,y_0)$处可微分，则该函数在该点沿任意方向l的方向导数为

$\frac{\partial f}{\partial l}|_{(x_0,y_0)}=f_x(x_0,y_0)\cos \alpha +f_y(x_0,y_0)\cos\beta$

其中$(\cos \alpha,\cos \beta)是l的方向余弦，即(\cos \alpha,\cos \beta)=\frac{l}{|l|}$

其几何意义为沿着l方向每移动一单位，f的函数值变化的单位数。

梯度向量$grad\  f(x,y)=\frac{\partial f}{\partial x}i+\frac{\partial f}{\partial y}j$

其几何意义为，f在这个方向变化最快

## 偏微分

二元函数二重偏微分有dxdx,dxdy,dydx,dydy。其中dxdy=dydx

## 积分

三种积分方法：凑元法，第二类换元法，分部积分法

### 凑微分法

$\int f(g(x))g'(x)dx=[\int f(u)du]_{u=g(x)}=F(g(x))$

本质上是对$[F[g(x)]]'=F'[g(x)]g'(x)$的逆运算。

例：$\int \sin^3 x dx=\int -sin^2 xd\cos x\\=\int (\cos^2 x-1)d\cos x\\=\int \cos^2 x d\cos x-\int1d\cos x\\=\frac{1}{3}\cos^3 x - cosx$

### 第二类换元法

$\int f(x)dx \overset{x=\phi(t)}{=}[\int f(\phi(t))\phi'(t)dt]_{t=\phi^{-1}(t)}$

例：$\int \sqrt{a^2-x^2}dx\\
令x=a\sin t \ \ \ (-\frac{\pi}{2}<t<\frac{\pi}{2})\\
原式=\int a\cos t\times a\cos tdt\\
=a^2\int \cos^2 tdt\\
=a^2\int \frac{1+\cos 2t}{2}dt\\
=\frac{a^2}{2}t+\frac{a^2}{4}\sin 2t + C\\
=\frac{a^2}{2}\arcsin \frac{x}{a} +\frac{a^2}{2}\sin t\cos t +C\\
=\frac{a^2}{2}\arcsin \frac{x}{a} + \frac{1}{2}\sqrt{a^2-x^2} + C$

### 分部积分法

$\int uv'dx=uv-\int vu'dx$

本质上是$(uv)'=u'v+v'u$其中等号右边一部分容易积分另一部分不容易积分时，把其中一部分换成另一部分。

$\int x\cos xdx=\int xd\sin x\\
=x\sin x - \int \sin xdx\\
=x\sin x + \cos x + C$\

### 有理函数的积分

* $\frac{P(x)}{Q(x)}$一定可以积分，其中$P(x), Q(x)$是x的多项式

* 三角有理函数$R(\sin x,\cos x)可以通过万能公式转变为t的多项式来积分$
  * $\tan \frac{x}{2}=u$
  * $\sin x=\frac{2\tan \frac{x}{2}}{1+\tan^2 \frac{x}{2}}=\frac{2u}{1+u^2}$
  * $\cos x=\frac{1-u^2}{1+u^2}$
  * $x=2\arctan u \Rightarrow dx=\frac{2du}{1+u^2}$

例：$\int \frac{1+\sin x}{\sin x(1+\cos x)}dx=\int \frac{1+\frac{2u}{1+u^2}}{\frac{2u}{1+u^2}(1+\frac{1-u^2}{1+u^2})}\times \frac{2}{1+u^2}du\\
=\frac{1}{4}u^2+u+\frac{1}{2}\ln |u| + C\\
=\frac{1}{4}(\tan \frac{x}{2})^2 + \tan \frac{x}{2} + \frac{1}{2}\ln |\tan \frac{x}{2}| + C$

### 常用积分技巧

* 有$\sqrt{a^2-x^2},\sqrt{a^2+x^2},\sqrt{x^2-a^2}$等出现的，可以用变换三角形，将x设为$a\sin t,a\cos t,a\sec t,a\tan t$等。
  利用公式$1-\sin^2 x =\cos^2 x，1+\tan^2 x=\sec^2 x$来消去根号。
* $\frac{g(x)}{f(x)}$形式积分，看一下f(x)是否可以分解因式成$u(x)\times v(x)$，如果可以拆项后分别积分
* $f(x)\sin x, f(x)cos(x)$等的积分，经常可以把$\sin xdx变成d\cos x$来降次
* 如被积函数为商形式，若分子次数比分母小，可试用倒置换 $x=\frac{1}{t}$

## 多元函数积分

多元函数定积分，可以根据曲面的形状，先积x再积y，或者先积y再积x

## 微分方程

微分方程是一个很深的话题。最基础的方法是分离变量法。把x和dx放在等号左侧，把y和dy放在等号右侧，分别积分。

