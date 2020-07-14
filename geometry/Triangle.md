# 三角形

## 符号表示

* $\triangle ABC$
* $a，b，c$为三边的长
* $A，B，C$为三个对应的三个内角的大小
* $R$表示外接圆半径，$r$表示内切圆半径
* $p$表示周长的一半，即$p=\frac{1}{2}(a+b+c)$
* $S_\triangle$表示其面积
* $h_a,h_b,h_c$表示对应边上的高
* $m_a,m_b,m_c$表示对应边上的中线长
* $t_a,t_b,t_c$表示对应角的角平分线长
* O表示圆的外心(Circumcenter)
* I表示圆的内心(Incenter)
* G表示圆的重心（Center of Gravity)
* H表示圆的垂心(Orthocenter)
* ?表示圆的旁心(escenter)

## 三角形面积

* $S_\triangle=\frac{1}{2}a*h_a=\frac{1}{2}b*h_b=\frac{1}{2}c*h_c$

* 海伦公式：$S_\triangle=\sqrt{p(p-a)(p-b)(p-c)}$

* 海伦公式变形：$S_\triangle=\frac{1}{4}\sqrt{(a+b+c)(a+b-c)(a+c-b)(b+c-a)}$

* 海伦—秦九韶三角形中线面积公式:

  $S_\triangle=\frac{1}{3}\sqrt{(m_a+m_b+m_c)(m_a+m_b-m_c)(m_a+m_c-m_b)(m_b+m_c-m_a)}$

* $S_\triangle=\frac{1}{2}(a+b+c)r=rp$

* $S_\triangle=\frac{abc}{4R}$

* $S=\frac{1}{2}ab\sin C = \frac{1}{2}bc\sin A = \frac{1}{2}ac\sin B$

* $S_\triangle=2R^2\sin A\sin B\sin C$

* $S_\triangle=\frac{a^2\sin B\sin C}{2\sin A}=\frac{h{_a^2}\sin A}{2\sin B\sin C}$

* $S_\triangle=r^2(\cot \frac{A}{2}+\cot \frac{B}{2}+ \cot \frac{C}{2})$

* $S_\triangle=Rr(\sin A+\sin B+\sin C)$

* $S_\triangle=\frac{abc}{2(a+b+c)}(\sin A +\sin B + \sin C)$

参考文献：https://zhuanlan.zhihu.com/p/25599977

## 五心

### 外心

三角形三条边垂直平分线的交点叫做三角形的外心(O)，即该三角形外接圆的圆心。它具有以下性质：
* 外心到三角形三顶点距离相等，就是外接圆的半径
* 在$\vartriangle ABC中，若\angle A是锐角，则\angle BOC=2\angle A。若\angle A是钝角，则\angle BOC=360-2\angle A$
* 设三角形的三条边长，外接圆的半径、面积分别为$a、b、c、R、S\triangle，则R=\frac{abc}{4S\triangle}$

### 内心

三角形三内角平分线的交点叫做三角形的内心(I)，即该三角形内切圆的圆心。它具有以下性质：
* 内心到三角形三边距离相等(逆定理不成立)，就是内切圆的半径

* $\triangle ABC$角平分线$AD$将底边BC分为BD和DC两段。则$\frac{AB}{AC}=\frac{DB}{DC}$

* 若I是$\vartriangle ABC$的内心，则$\angle BIC=90+\frac{1}{2}\angle A,\angle CIA=90+\frac{1}{2}\angle B,\angle AIB=90+\frac{1}{2}\angle C$

* 设I为$\vartriangle ABC$的内心，BC=a，AC=b，AB=c，I在BC、AC、AB上的射影分别为D、E、F；内切圆半径为r，

  令p=$\frac{a+b+c}{2}$，则

  * $S_△ABC=pr$
  * $r=2S_\triangle ABC/(a+b+c)$
  * AE=AF=p-a，BD=BF=p-b，CE=CD=p-c
  * abcr=p·AI·BI·CI

*  三角形一内角平分线与其外接圆的交点到另两顶点的距离与到内心的距离相等；反之，若I为△ABC的∠A平分线AD(D在△ABC的外接圆上)上的点，且DI=DB，则I为△ABC的内心。

* 设I为△ABC的内心，BC=a，AC=b，AB=c，∠A的平分线交BC于K,交△ABC的外接圆于D，则$\frac{AI}{KI}=\frac{AD}{DI}=\frac{DI}{DK}=\frac{b+c}{a}$

### 重心

三角形三条中线的交点叫做三角形的重心(G)，它具有以下性质：
* 重心到顶点的距离是它对对边中点距离的两倍
* 若G是$\vartriangle ABC$的重心，则$S\vartriangle GBC=S\vartriangle GCA=S\vartriangle GAB=\frac{1}{3}S\vartriangle ABC$
* 重心坐标为三顶点坐标平均值 [(X1+X2+X3)/3,(Y1+Y2+Y3)/3]
* 重心是到三角形三顶点的距离平方和最小的点

### 垂心

三角形三条边上高所在的直线的交点叫做三角形的垂心(H)，它具有以下性质：
<img src="images\orthoCenter.png" alt="orthoCenter" style="zoom:50%;" />

* 图中共有六祖四点共圆
  * A,F,H,E
  * B,D,H,F
  * C,E,H,D
  * A,B,D,E (见证明1)
  * B,C,E,F
  * A,C,D,F
* 图中共有三组(每组四个)相似直角三角形，例如
  $\triangle AFH \sim \triangle ADB \sim \triangle CDH \sim \triangle CFB$
* AH * HD = BH * HE = CH * HF
* 垂心H关于三边的对称点均在$\triangle ABC$的外接圆上
* H,A,B,C中任一点是另外三点连成的三角形的垂心
* △ABC,△ABH,△BCH,△ACH的外接圆是等圆
* $\triangle ABC$的内接三角形(即顶点在$\triangle ABC$的边上)中，以垂足$\triangle DEF$的周长最短

### 旁心

与三角形的一边及其他两边的延长线都相切的圆叫做三角形的旁切圆，旁切圆的圆心叫做三角形旁心
<img src="images\escenter.png" alt="escenter" style="zoom:50%;" />

* 三角形的一条内角平分线与其他两个角的外角平分线交于一点，该点即为三角形的旁心。
* 三角形有三个旁切圆，三个旁心。旁心一定在三角形外。
* 旁心到三角形三边的距离相等。
* 直角三角形斜边上的旁切圆的半径等于三角形周长的一半。
* ∠BI1C=90°-∠A/2.
* AP1=r1·cot(A/2)=(a+b+c)/2.
* ∠AI1B=∠C/2.
* S⊿ABC=r1(b+c-a)/2.
* r1=rp/(p-a).
* r1=(p-b)(p-c)/r.
* 1/r1+1/r2+1/r3=1/r.
* r1=r/(tanB/2)(tanC/2).

### 五心间的关系

* 若I是$\vartriangle ABC$的内心，AI延长线交$\vartriangle ABC$外接圆于点D，则有DI=DB=DC，即D为$\vartriangle BCI$的外心 (见证明2)，其逆命题也成立。
* 锐角三角形的垂心是它垂足三角形的内心；或者说，三角形的内心是它旁心三角形的垂心(见证明3)
* 三角形的外心是它的中点三角形的垂心
* 三角形的重心也是它的中点三角形的重心
* 三角形的中点三角形的外心也是其垂足三角形的外心
* 三角形的任一顶点到垂心的距离，等于外心到对边的距离的二倍(见证明4)
* 锐角三角形的外心到三边的距离之和等于其内切圆与外接圆半径之和

### 五心口诀

三角形有五颗心，重外垂内和旁心，

五心性质很重要，认真掌握莫记混．
#### 重心记忆口诀

三条中线定相交，交点位置真奇巧，

交点命名为“重心”，重心性质要明了，

重心分割中线段，数段之比听分晓；

长短之比二比一，灵活运用掌握好．

#### 外心记忆口诀
三角形有六元素，三个内角有三边．

作三边的中垂线，三线相交共一点．

此点定义为外心，用它可作外接圆．

内心外心莫记混，内切外接是关键．

#### 垂心记忆口诀
角形上作三高，三高必于垂心交．

高线分割三角形，出现直角三对整，

直角三角形有十二，构成六对相似形，

四点共圆图中有，细心分析可找清.

#### 内心记忆口诀

三角对应三顶点，角角都有平分线，

三线相交定共点，叫做“内心”有根源；

点至三边均等距，可作三角形内切圆，

此圆圆心称“内心”，如此定义理当然．

五心性质别记混，做起题来真是好。

## 三角函数

### 正弦定理

在$\triangle ABC$ 中，$\frac{a}{sinA}=\frac{b}{sinB}=\frac{c}{sinC}=2R$，其中$a、b、c$分别为$\angle A,\angle B,\angle C$所对的边，$R$为$\triangle ABC$外接圆半径

### 余弦定理

* $a^2 = b^2 + c^2 -2bc\cos A$
* $b^2 = a^2 + c^2 -2ac\cos B$
* $c^2 = a^2 + b^2 -2ab\cos C$
* $\cos A = \frac{b^2 + c^2 - a^2}{2bc}$
* $\cos B = \frac{a^2 + c^2 - b^2}{2ac}$
* $\cos C = \frac{a^2 + b^2 - c^2}{2ab}$



### 证明1

定理:图见垂心章节，求证ABDE四点共圆

证明：连接DE。

$\angle ADB = \angle AEB = 90$

$\triangle ADB和 \triangle AEB$的外心都在AB的中点上，ABDE四点共圆，圆心是AB中点​




### 证明2

定理：若I是$\vartriangle ABC$的内心，CI延长线交$\vartriangle ABC$外接圆于点D，则有DI=DA=DB，即D为$\vartriangle AIB$的外心
<img src="images\IncenterAndOutCenter.png" alt="IncenterAndOutCenter" style="zoom:50%;" />


证明：
$$
\angle AOD = 2\angle ACD (圆的弦对应的圆心角是圆周角的两倍)\\
\angle BOD = 2\angle BCD\\
\angle ACD = \angle BCD\\
\therefore \angle AOD = \angle BOD\\
AD = BD (圆内同样大小的角对应的弦的长度相同)\\

\because \angle AID = \angle ACD + \angle CAI (三角形外角等于非相邻的两内角和)\\
=\angle BCD + \angle CAI\\
=\angle BAD + \angle CAI\\
=\angle BAD + \angle IAB\\
=\angle IAD\\
\therefore ID=AD (等角对等边)

\therefore ID=AD=BD\\
得证
$$

### 证明3：

定理：三角形的垂心是它垂足三角形的内心

证明：图见垂心章节

连接DE,EF,FD

$\because AFHE四点共圆$

$\therefore \angle BAC + \angle FHE= 180^{\circ}$

$\angle BAC + \angle BHC = 180^{\circ}$

$\because AFDC四点共圆(见证明1)$

$\therefore \angle BAC + \angle FDC = 180^{\circ}$

$\therefore \angle BHC = \angle FDC$

$\because \angle BCF = \angle FCB $

$\therefore \triangle BHC \sim \triangle FDC$

$\therefore \angle HBC = \angle CFD$

$\because BCEF四点共圆$

$\therefore \angle EBC = \angle EFC$

$\therefore \angle EFC = \angle CFD$

同理 $\angle FEB= \angle BED,\angle FDA=\angle ADE$

H为$\triangle DEF$的内心

得证

### 证明4

定理：三角形的任一顶点到垂心的距离，等于外心到对边的距离的二倍

<img src="images\OrthoCenterAndCircumCenter.png" alt="IncenterAndOutCOrthoCenterAndCircumCenterenter" style="zoom:50%;" />

https://www.geogebra.org/geometry/ysnmvfjq

证明：连接CO并延长，交$\triangle ABC$外接圆于J点。连接AJ,JB,OB
$$
\because CJ为圆的直径\\
\therefore \angle JBC = 90^{\circ}\\
\because OI \perp BC (外心定义)\\
\therefore OI \parallel JB\\
\triangle OIC \sim \triangle JBC\\
\because BC = 2IC\\
\therefore JB=2OI\\
\because \angle JAB = \angle JCB (圆同弦对同角)\\
\angle JCB = \angle OBC = 1/2（180^{\circ}-\angle BOC = 90^{\circ}-\angle BAC\\
\angle ABE = 90^{\circ}-\angle BAC\\
\therefore \angle JAB = \angle ABE\\
\therefore AJ \parallel BH\\
又 JB \parallel AH\\
\therefore AJBH为平行四边形\\
\therefore JB = AH\\
\therefore AH = 2OI\\
$$
得证

