线代23秋期中试题答案 发布版

<hr style="border: 1px solid black;">
Q1 (1)A    (2)B（存疑, 一说D）    (3)D    (4)B    (5)D

Q2(1)21

(2)$-A^{-1}CB^{-1}$

(3)1or-3 （存疑，一说 1 or -2）

(4)$\begin{aligned}\left[\begin{matrix}-\frac{19}{11}\\-\frac{5}{11}\end{matrix}\right]\end{aligned}$

(5)$\begin{aligned} \frac{1}{\sqrt{ 6 }} \left[\begin{matrix} 1\\2\\1\end{matrix}\right]\text{or}-\frac{1}{\sqrt{ 6 }} \left[\begin{matrix} 1\\2\\1\end{matrix}\right]\end{aligned}$

<hr style="border: 1px solid black;">


Q3
A basis for $C(A)$ $$\left\{\begin{bmatrix}1\\0\\-1\\2\end{bmatrix},\begin{bmatrix}2\\1\\1\\0\end{bmatrix},\begin{bmatrix}1\\1\\3\\1\end{bmatrix}\right\}.$$
A basis for $C(A^T)$
$$\left.\left\{\left[\begin{array}{c}1\\0\\1\\0\\3\end{array}\right.\right],\left[\begin{array}{c}0\\1\\2\\0\\1\end{array}\right],\left[\begin{array}{c}0\\0\\0\\1\\1\end{array}\right]\right\}\text{or}\left.\left\{\left[\begin{array}{c}1\\2\\5\\1\\6\end{array}\right.\right],\left[\begin{array}{c}0\\1\\2\\1\\2\end{array}\right],\left[\begin{array}{c}-1\\1\\1\\3\\1\end{array}\right]\right\}$$
A basis for $N(A)$
$$\left.\left\{\left[\begin{array}{c}{-1}\\{-2}\\{1}\\{0}\\\end{array}\right.\right],\left[\begin{array}{c}{-3}\\{-1}\\{0}\\{-1}\\\end{array}\right]\right\}.$$

A basis for $N(A^T)$
$$\left\{\left[\begin{array}{c}-5\\13\\-3\\1\end{array}\right]\right\}.$$

$$(b)\left.\left[\begin{array}{cc}5\\2\\1\\2\end{array}\right.\right]$$

Q4
Gaussian Eliminations give:
$$\begin{align}
&\left[\begin{array}{ccccc}1&-1&-1&\vdots&2&2\\2 & a &1&\vdots&1&a\\-1&1&a&\vdots&-a-1&-2\end{array}\right] \\\end{align}$$
$$\begin{align}\to&\left[\begin{array}{ccccc}1&-1&-1&\vdots&2&2\\0 & a+2 &3&\vdots&-3&a-4\\0&0&a-1&\vdots&0&0\end{array}\right]
\end{align}$$

If $a = -2$, then $rankA = 2 \neq 3 = rank(A \vdots B)$,$AX=B$ has no solution.

If $a \neq 1$ and $a \neq -1, AX=B$ has a unique solution.
$$\left.\left[\begin{array}{cccc}1&-1&-1&1&2\\0&a+2&3&1&-3\\0&0&a-1&1&1-a\end{array}\right.\right]\Rightarrow x=\left[\begin{array}{c}1\\0\\-1\end{array}\right]. $$
$$\begin{aligned}
&\left.\left[\begin{array}{cccc}1&-1&-1&\vdots&2\\0&a+2&3&\vdots&-3\\0&0&a-1&\vdots&1-a\end{array}\right.\right]\Rightarrow x=\left[\begin{array}{c}1\\0\\-1\end{array}\right]. \\
\end{aligned}$$
$$
\left.\left[\begin{array}{cccc}1&-1&-1&\vdots&z\\0&a+2&3&\vdots&a-4\\0&0&a-1&\vdots&0\end{array}\right.\right]\Rightarrow X=\left[\begin{array}{c}\frac{3a}{a+2}\\\frac{a-4}{a+2}\\0\end{array}\right]. $$
$$
\left.X=\left[\begin{array}{cc}1&\frac{3a}{a+2}\\0&\frac{a-4}{a+2}\\-1&0\end{array}\right.\right]
$$
If $a = 1$, $Ax=B$ has infinitely many solutions
$$\begin{aligned}&\begin{bmatrix}1&-1&-1&-2\\0&3&3&-3\\0&0&0&1&0\end{bmatrix}\Rightarrow x=\begin{bmatrix}1\\-1\\0\end{bmatrix}+k_{1}\begin{bmatrix}0\\-1\\1\end{bmatrix}\\&\begin{bmatrix}1&-1&-1&2\\0&3&3&1&-3\\0&0&0&1&0\end{bmatrix}\Rightarrow x=\begin{bmatrix}-1\\-1\\0\end{bmatrix}+k_{2}\begin{bmatrix}0\\-1\\1\end{bmatrix}\\&\Rightarrow X=\begin{bmatrix}1&1\\-k_{1}-1&-k_{2}-1\\k_{1}&k_{2}\end{bmatrix},\quad k_{1},k_{2}\quad\mathrm{anbitrary~constants}.\end{aligned}$$

Q5
(a)Let $X,Y \in M_{2\times2}(R) \text{ and } C\in R$, than we have
$$\begin{aligned}T\left(CX+Y\right)&=\begin{bmatrix}tr&A^{T}\left(CX+Y\right)\\tr&B^{T}\left(CX+Y\right)\\tr&C^{T}\left(CX+Y\right)\end{bmatrix}\\&=c\left[\begin{array}{c}tr(A^{T}X)\\tr(B^{T}X)\\tr(C^{T}X)\end{array}\right]+\begin{bmatrix}tr(A^{T}X)\\tr(B^{T}Y)\\tr(C^{T}Y)\end{bmatrix}\\&=cT(X)+T(Y)\end{aligned}$$
(b)
$$\begin{aligned}&T\left(V_{1}\right)=\begin{bmatrix}1\\0\\0\end{bmatrix}=1\begin{bmatrix}1\\0\\0\end{bmatrix}_{=w_{1}}+0\begin{bmatrix}0\\1\\0\end{bmatrix}_{=w_{2}}+0\begin{bmatrix}0\\0\\1\end{bmatrix}_{=w_{3}}\\&T\left(V_{2}\right)=\begin{bmatrix}-1\\0\\0\end{bmatrix}=-1\begin{bmatrix}1\\0\\1\end{bmatrix}+0\begin{bmatrix}0\\1\\0\end{bmatrix}+0\cdot\begin{bmatrix}0\\0\\1\end{bmatrix}\\\end{aligned}
$$
$$\begin{aligned}&T\left(V_{3}\right)=\begin{bmatrix}0\\1\\1\end{bmatrix}=0\begin{bmatrix}1\\0\\0\end{bmatrix}+1\cdot\begin{bmatrix}0\\1\\0\end{bmatrix}+1\cdot\begin{bmatrix}0\\0\\1\end{bmatrix}\\&T\left(V_{4}\right)=\begin{bmatrix}0\\1\\-1\end{bmatrix}=0\begin{bmatrix}1\\0\\0\end{bmatrix}+1\cdot\begin{bmatrix}0\\0\\0\end{bmatrix}+-1\cdot\begin{bmatrix}0\\0\\1\end{bmatrix}\\&\end{aligned}$$
Therefore,the matix representation of T with respect to$V_{1},V_{2},V_{3},V_{4},V_{4}$, and $W_{1},V_{2},W_{3}$ , is:
$$\begin{aligned}&\begin{bmatrix}1&-1&0&0\\0&0&1&1\\0&0&1&-1\end{bmatrix}.\end{aligned}$$

(c)Since $T(A)=\begin{bmatrix}2\\0\\0\end{bmatrix},T(B)=\begin{bmatrix}0\\1\\0\end{bmatrix}, T(C)=\begin{bmatrix}0\\0\\1\end{bmatrix}$,We can take X to be
$$\begin{aligned}&\frac{1}{2}A-2B+C\\&=\left[\begin{array}{cc}y_2&0\\0&-y_2\end{array}\right]-\left[\begin{array}{cc}0&2\\-0&0\end{array}\right]+\left[\begin{array}{cc}0&0\\1&0\end{array}\right]\\&=\left[\begin{array}{cc}y_2&-2\\1&-y_2\end{array}\right].\end{aligned}$$


<hr style="border: 1px solid black;">

Q6  Apply Elementary Row and Column Operations to A and C to obtain $D_{1}= \begin{bmatrix} I_{1}& 0\\ 0& 0\end{bmatrix}$ for A and $D_2=\begin{bmatrix}I_{3}&0\\0&0\end{bmatrix}$for C.

Where $r= rankA,s= rank C$.
Let $M=\left[\begin{array}{cc}A&B\\0&C\end{array}\right]$. Then M can be converted to $M_{1}=\left[\begin{array}{ccc}D_{1}&C_{1}\\0&D_{2}\end{array}\right]$ via elementary row and column operations.

Furthermore, the pivots in $D_{1}$ and $D_{2}$ can be used to eliminate the nonzero entries in $C_1$, to obtain
$$M_{2}=\left[\begin{matrix}I_{r}&0&0&0\\0&0&0&C_{2}\\0&0&I_{s}&0\\0&0&0&0\end{matrix}\right].$$
In conclusion,
$\begin{aligned}rankM&=rankM_{1}=rankM_{2}=r+s+rankC_{2}\\&\geq r+s= rank A+ rank C\end{aligned}$



