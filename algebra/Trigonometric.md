# 三角函数

注，本章节仅含存三角函数。和三角形，圆形相关的三角函数参见三角形和圆形章节

- $\sin \alpha=\frac{y}{r}，\cos \alpha=\frac{x}{r}，\tan \alpha=\frac{y}{x}$

- 正弦函数$y=\sin x$在区间
  $\left[-\frac{\pi}{2}, \frac{\pi}{2}\right]$上，从-1 增大到 1, 是递增的; 在区间$\left[\frac{\pi}{2}, \frac{3 \pi}{2}\right]$上，从 1 减少到-1，是递減的。

- 余弦函数$y=\cos x$在区间
  $\left[-\pi, 0\right]$上，从-1 增大到 1, 是递增的; 在区间$\left[0, \pi\right]$上，从 1 减少到-1，是递減的。

- 正切函数在每一个开区间$\left(-\frac{\pi}{2}+k \pi, \frac{\pi}{2}+k \pi\right)(k \in \mathbf{Z})$上都是单调递增的

- $\begin{array}{l}
\sin ^{2} \alpha+\cos ^{2} \alpha=1\\
\tan ^{2} \alpha+1=\sec ^{2} \alpha\\
\cot ^{2} \alpha+1=\csc ^{2} \alpha\\
\tan \alpha=\frac{\sin \alpha}{\cos \alpha}\end{array}$

  <img src="images\RelationHexagon.png" alt="RelationHexagon" style="zoom:50%;" />

- $\begin{array}{l}
  \sin (-\alpha)=-\sin \alpha \\
  \cos (-\alpha)=\cos \alpha \\
  \tan (-\alpha)=-\tan \alpha
  \end{array}$

- $\begin{array}{l}
  \sin (\pi \pm a)=\mp \sin \alpha \\
  \cos (\pi \pm \alpha)=-\cos \alpha \\
  \tan (\pi \pm \alpha)=\pm \tan \alpha \\
  \end{array}$

- $\begin{array}{l}
  \sin \left(\frac{\pi}{2} \pm \alpha\right)=\cos \alpha \\
  \cos \left(\frac{\pi}{2} \pm \alpha\right)=\mp \sin \alpha \\
  \tan \left(\frac{\pi}{2} \pm \alpha\right)=\mp \cot \alpha \\
  \end{array}$

- $\begin{array}{l}\sin (\alpha \pm \beta)=\sin \alpha \cos \beta \pm \cos \alpha \sin \beta \\
\cos (\alpha \pm \beta)=\cos \alpha \cos \beta \mp \sin \alpha \sin \beta \\
\tan (\alpha \pm \beta)=\frac{\tan \alpha \pm \tan \beta}{1 \mp \tan \alpha \tan \beta} \\
\end{array}$

- $\begin{array}{l}
\sin 2\alpha=2\sin\alpha\cos\alpha \\
\cos 2\alpha=\cos^2\alpha-\sin^2\alpha = 2\cos^2-1=1-2\sin^2 \alpha \\
\tan 2\alpha=\frac{2\tan \alpha}{1-\tan^2 \alpha}
\end{array}$

- $积化和差公式 \\
\begin{array}{l}
\sin \alpha \sin \beta=-\frac{1}{2}[\cos (\alpha+\beta)-\cos (\alpha-\beta)] \\
\sin \alpha \cos \beta=\frac{1}{2}[\sin (\alpha+\beta)+\sin (\alpha-\beta)] \\
\cos \alpha \sin \beta=\frac{1}{2}[\sin (\alpha+\beta)-\sin (\alpha-\beta)] \\
\cos \alpha \cos \beta=\frac{1}{2}[\cos (\alpha+\beta)+\cos (\alpha-\beta)] \\
\end{array}$

* $和差化积公式 \\
\begin{array}{l}
\cos x+\cos y=2 \cos \frac{x+y}{2} \cos \frac{x-y}{2} \\
\cos x-\cos y=-2 \sin \frac{x+y}{2} \sin \frac{x-y}{2} \\
\sin x+\sin y=2 \sin \frac{x+y}{2} \cos \frac{x-y}{2} \\
\sin x-\sin y=2 \cos \frac{x+y}{2} \sin \frac{x-y}{2}
\end{array}$

- $半角公式 \\
\begin{array}{l}
\sin \frac{a}{2}=\pm \sqrt{\frac{1-\cos \alpha}{2}} \\
\cos \frac{a}{2}=\pm \sqrt{\frac{1+\cos \alpha}{2}} \\
\tan \frac{a}{2}=\pm \sqrt{\frac{1-\cos a}{1+\cos a}}
\end{array}$

- $万能公式 \\
  \begin{array}{l}
\sin a=\frac{2 \tan \frac{a}{2}}{1+\tan ^{2} \frac{a}{2}} \\
\cos a=\frac{1-\tan ^{2} \frac{a}{2}}{1+\tan ^{2} \frac{a}{2}} \\
\tan a=\frac{2 \tan \frac{a}{2}}{1-\tan ^{2} \frac{a}{2}}
\end{array}$

## 三角函数与向量

- 向量的数量积(内积) $a \cdot b=|a||b| \cos \langle a, b\rangle$
- 向量 $a$ 在向量 $b$ 上的投影 $|a| \cos \langle a, b\rangle$
- $a \perp b \Leftrightarrow a \cdot b=0 \Leftrightarrow |a| \cos \langle a, b\rangle=0$
- 向量加减内积运算满足交换律，结合律，分配律

## 解题技巧

- 一个包含$\sin$和$\cos$的算式，可以除以$\sin^2x+\cos^2x$，然后分子分母同时除以$\cos^2x$，变成只有$\tan$的算式

- 同时有$\alpha$和$\beta$的方程组，可以写成一边是$\alpha$另一边是$\beta$，然后利用$\sin^2 \alpha + \cos^2 \alpha=1$消去一个角度

- 三角函数换算表。查表用，无需记忆。严格讲每个根号前应有正负号。

  $\begin{array}{|c|c|c|c|c|c|}
  \hline \text { 函数 } & \sin & \cos & \tan & \cot & \sec & \csc \\
  \hline \sin \theta & \sin \theta & \sqrt{1-\cos ^{2} \theta} & \frac{\tan \theta}{\sqrt{1+\tan ^{2} \theta}} & \frac{1}{\sqrt{1+\cot ^{2} \theta}} & \frac{\sqrt{\sec ^{2} \theta-1}}{\sec \theta} & \frac{1}{\csc \theta} \\
  \hline \cos \theta & \sqrt{1-\sin ^{2} \theta} & \cos \theta & \frac{1}{\sqrt{1+\tan ^{2} \theta}} & \frac{\cot \theta}{\sqrt{1+\cot ^{2} \theta}} & \frac{1}{\sec \theta} & \frac{\sqrt{\csc ^{2} \theta-1}}{\csc \theta} \\
  \hline \tan \theta & \frac{\sin \theta}{\sqrt{1-\sin ^{2} \theta}} & \frac{\sqrt{1-\cos ^{2} \theta}}{\cos \theta} & \tan \theta & \frac{1}{\cot \theta} & \sqrt{\sec ^{2} \theta-1} & \frac{1}{\sqrt{\csc ^{2} \theta-1}} \\
  \hline \cot \theta & \frac{\sqrt{1-\sin ^{2} \theta}}{\sin \theta} & \frac{\cos \theta}{\sqrt{1-\cos ^{2} \theta}} & \frac{1}{\tan \theta} & \cot \theta & \frac{1}{\sqrt{\sec ^{2} \theta-1}} & \sqrt{\csc ^{2} \theta-1} \\
  \hline \sec \theta & \frac{1}{\sqrt{1-\sin ^{2} \theta}} & \frac{1}{\cos \theta} & \sqrt{1+\tan ^{2} \theta} & \frac{\sqrt{1+\cot ^{2} \theta}}{\cot \theta} & \sec \theta & \frac{\csc \theta}{\sqrt{\csc ^{2} \theta-1}} \\
  \hline \csc \theta & \frac{1}{\sin \theta} & \frac{1}{\sqrt{1-\cos ^{2} \theta}} & \frac{\sqrt{1+\tan ^{2} \theta}}{\tan \theta} & \sqrt{1+\cot ^{2} \theta} & \frac{\sec \theta}{\sqrt{\sec ^{2} \theta-1}} & \csc \theta \\
  \hline
  \end{array}$
