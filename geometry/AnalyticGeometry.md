# 平面解析几何



- 两点距离 $d(A, B)=|A B|=\sqrt{\left(x_{2}-x_{1}\right)^{2}+\left(y_{2}-y_{1}\right)^{2}}$

- 中点公式 $x=\frac{x_{1}+x_{2}}{2}, y=\frac{y_{1}+y_{2}}{2}$

## 直线

- 直线$y=kx+b(k\neq 0)$的斜率是$k$。垂直于$x$轴的直线斜率不存在

- 直线的一般式方程 $A x+B y+C=0 \quad\left(A^{2}+B^{2} \neq 0\right)$

- 过$A(x_1,y_1)，B(x_2,y_2)$两点的直线方程 $k=\tan \theta = \frac{y_{2}-y_{1}}{x_{2}-x_{1}} \left(x_{1} \neq x_{2}\right)=\frac{\Delta y}{\Delta x}(\Delta x \neq 0)$

- $\begin{aligned}
  &l_{1} / / l_{2} \Leftrightarrow k_1=k_2 且 b_1 \neq b_2\\
  &l_{1} 与 l_{2} \text { 重合 } \Leftrightarrow k_1=k_2 \text { 且 } b_1=b_2
  \end{aligned}$

- $l_{1} \perp l_{2} \Leftrightarrow A_{1} A_{2}+B_{1} B_{2}=0 \Leftrightarrow k_{1} k_{2}=-1$

- 点$(x_1,y_1)$到直线的距离 $d=\frac{\left|A x_{1}+B y_{1}+C\right|}{\sqrt{A^{2}+B^{2}}}$

## 圆

- 圆的方程 $(x-a)^{2}+(y-b)^{2}=r^{2}$

- 圆的一般方程 $x^{2}+y^{2}+D x+E y+F=0 \quad (D^{2}+E^{2}-4 F>0)$

## 椭圆

- 椭圆标准方程 $\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1 \quad(a>b>0)$

  两个焦点在x轴上，坐标分别为$F_{1}(-c, 0), F_{2}(c, 0), \text { 这里 } c^{2}=a^{2}-b^{2}$

  如果焦点在y轴上，则有$(b>a>0)$

- 离心率 $e=\frac{c}{a}=\sqrt{1+\frac{b^2}{a^2}}$

## 双曲线

- 在平面内到两个定点$F_1, F_2$的距离之差的绝对值等于定值$2a(0<2a<|F_1F_2|)$的点的轨迹叫做双曲线.  这两个定点叫做双曲线的焦点，两焦点的距离叫做双曲线的焦距
- 双曲线标准方程 $\frac{x^{2}}{a^{2}}-\frac{y^{2}}{b^{2}}=1(a>0, b>0)$
- 离心率$e=\frac{c}{a} \quad (c为半焦距)$

## 抛物线

- $平面内到一个定点F和一条定直线了l(F \notin l)的距离相等的点的轨迹叫做抛物线。 \\ 点F叫做抛物线的焦点，直线l叫做抛物线的准线，焦点到准线的距离(定长p)叫做抛物线的焦参数$

- 抛物线的标准方程 

  $y^{2}=2px (p>0)$

- $\begin{array}{|c|c|c|c|c|} \hline 标准方程 & y^2=2px & y^2=-2px & x^2=2py & x^2=-2py  \\
  & (p>0)  &  (p>0)  &  (p>0)  &  (p>0)  \\
  \hline 对称轴 & x轴 & x轴 & y轴 & y轴 \\ \hline 开口 & 向右 & 向左 & 向上 & 向下 \\ \hline 顶点 & 原点 & 原点 & 原点 & 原点 \\
  \hline 焦点坐标 & \left(\frac{p}{2}, 0\right) & \left(-\frac{p}{2}, 0\right) & \left(0, \frac{p}{2}\right) & \left(0,-\frac{p}{2}\right)  \\
  \hline准线方程 & x=-\frac{p}{2}  &  x-\frac{p}{2}  &  y=-\frac{p}{2}  &  y=\frac{p}{2} \\ \hline 
  \end{array}$