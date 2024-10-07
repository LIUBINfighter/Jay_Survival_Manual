
### 快速对答案
一、D D C C A

二、
$$\begin{align}
&(1)A^{-1}=\begin{bmatrix}1\\-a&1\\(3a-b)/2&-3/2&1/2\end{bmatrix}&&(2)2 \\
&(3)4^{2023}A=4^{2023}\begin{bmatrix}1&-1&1\\-1&1&-1\\2&-2&2\end{bmatrix}&&(4)\begin{bmatrix}\begin{aligned}\frac{7}{3}\end{aligned}\\\begin{aligned}\frac{10}{3}\end{aligned}\end{bmatrix}
\end{align}$$

三、$A=LU\left.=\left[\begin{array}{ccc}{1}&&\\{2}&{1}&\\{1}&{2}&{1}\\\end{array}\right.\right]\left[\begin{array}{ccc}{1}&{-2}&{3}\\{}&{-1}&{-5}\\{}&{}&{0}\\\end{array}\right]$

四、(a)
$(1)C(A)=span\left\{\begin{bmatrix}2\\1\\4\\-1\end{bmatrix},\begin{bmatrix}4\\1\\10\\-5\end{bmatrix},\begin{bmatrix}6\\3\\2\\7\end{bmatrix}\right\}$

$(2)\left.C\left(A^{T}\right)=\mathrm{Span}\left[\left[\begin{array}{c}{0}\\{2}\\{4}\\{1}\\{6}\end{array}\right.\right],\left[\begin{array}{c}{0}\\{1}\\{1}\\{1}\\{3}\end{array}\right],\left[\begin{array}{c}{0}\\{4}\\{10}\\{1}\\{2}\end{array}\right]\right]$

$(3)\left.X=K_{1}\left[\begin{array}{c}{1}\\{0}\\{0}\\{0}\\{0}\\\end{array}\right.\right]+K_{4}\left[\begin{array}{c}{0}\\{-\frac{3}{2}}\\{\frac{1}{2}}\\{1}\\{0}\\\end{array}\right]\left(k_{1},k_{2}\in\mathbb{R}\right)$

$(4)y=k_{0}\left[\begin{array}{c}-1\\-1\\1\\1\end{array}\right],k_{0} \in R$

(b)$$x=x_{p}+x_{n}=\begin{bmatrix}1\\-5\\1\\3\\1\end{bmatrix}+k_{1}\begin{bmatrix}1\\0\\0\\0\\0\end{bmatrix}+k_{4}\begin{bmatrix}0\\-3/2\\1/2\\1\\0\end{bmatrix}\quad k_{1},k_{4}\in\mathbb{R}$$

五、略，解析部分有方法

六、证明略

七、
$$\begin{align}
&(AB)^{2}=\begin{bmatrix}72&0&-36\\-\frac{27}{2}&81&-54\\-18&0&9\end{bmatrix} \\
&BA=9I
\end{align}$$

### 填空及大题详解
二、(1)
$$\begin{align}
\mathbf{[}A \quad I\mathbf{]} & =\left[\begin{array}{ccccc}1&&&\vdots&1&&\\a & 1 &&\vdots&&1&\\b&3&2&\vdots&&&1\end{array}\right] \to \left[\begin{array}{ccccc}1&&&\vdots&1&&\\0 & 1 &&\vdots&-a&1&\\0&3&2&\vdots&-b&0&1\end{array}\right] \\ \\
& \to \left[\begin{array}{ccccc}1&&&\vdots&1&&\\0 & 1 &&\vdots&-a&1&\\0&0&2&\vdots&3a-b&-3&1\end{array}\right]
 \\
& \to  \left[\begin{array}{ccccc}1&&&\vdots&1&&\\ & 1 &&\vdots&-a&1&\\&&1&\vdots& {(3a-b)}/2&-3/2&1/2\end{array}\right]=\mathbf{[}I \quad A^{-1}\mathbf{]}\\
\end{align}$$

(2)法1令
$$\begin{aligned}
&A_{4\times3}=\left[\begin{matrix}1&& \\&&1 \\0&0&0 \\0&0&0 \\\end{matrix}\right]\\&
\end{aligned}$$

$$
\begin{aligned}
&AB=\left.\left[\begin{array}{cc}{1}&&\\&&{1}\\{\cdots}&\cdots&\cdots\\{\cdots}&\cdots&\cdots\\\end{array}\right.\right]\left[\begin{array}{cc}{1}&{0}&{2}\\{0}&{2}&{0}\\{-1}&{0}&{3}\\\end{array}\right]=\left[\begin{array}{cc}{1}&0&{2}\\{-1}&{0}&{3}\\{0}&{0}&{0}\\{0}&{0}&{0}\\\end{array}\right] \\&\to R(AB)=2
\end{aligned}$$

法2
$$\begin{align}
&R(A)=2,R(B)=3 \\
&R(AB)\geq R(A)+R(B)-n=2+3-3=2\\
&R(AB)\leq min\{R(A),R(B)\}=2 \\
 \\
&\implies R(AB)=2
\end{align}$$

(3)剥蒜（爆算）法 直接计算$A^2,A^3$的得出规律

(4)$A=\left[\begin{matrix}0&1 \\ 0&1 \\ 1&1\end{matrix}\right],b=\left[\begin{matrix}2 \\ 3 \\ 6\end{matrix}\right]$

三、
$$\begin{aligned}&A=\begin{bmatrix}1&-2&3\\2&-5&1\\4&-4&-7\end{bmatrix}\\&E_{21}(-2)A=\begin{bmatrix}1&-2&3\\0&-1&-5\\1&-4&-7\end{bmatrix}\\&E_{31}(-1)E_{21}(-2)A=\begin{bmatrix}1&-2&3\\0&-1&-5\\0&-2&-10\end{bmatrix}\\\end{aligned}
$$

$$\begin{aligned}&E_{32}(-2)E_{31}(-1)E_{31}(-2)A=\begin{bmatrix}1&-2&-3\\0&-1&-5\\0&0&0\end{bmatrix}\\&A=E_{21}^{-1}(-2)E_{31}(-1)^{-1}E_{32}^{-1}(-2)\begin{bmatrix}1&-2&3\\0&-1&-5\\0&0&0\end{bmatrix}\\&=\begin{bmatrix}1&&\\2&1&\\1&2&1\end{bmatrix}\begin{bmatrix}1&-2&3\\0&-1&-5\\0&0&0\end{bmatrix}=LU\end{aligned}$$

四、(a)          (1)C(A),对A行变换
$$\begin{aligned}&&A\to\left[\begin{array}{cccc}0&\boxed2&0&3&0\\0&0&\boxed2&-1&0\\0&0&0&0&\boxed{10}\\0&0&0&0&0\end{array}\right]\Rightarrow C(A)=span\left\{\begin{bmatrix}2\\1\\4\\-1\end{bmatrix},\begin{bmatrix}4\\1\\10\\-5\end{bmatrix},\begin{bmatrix}6\\3\\2\\7\end{bmatrix}\right\}\end{aligned}$$

$$\begin{aligned}&(2)C(A^{T})\quad\text{对}A^{T}\text{行变换}\\A^{T}&=\begin{bmatrix}0&0&0&0\\2&1&4&-1\\4&1&10&-5\\1&1&1&1\\0&3&2&7\end{bmatrix}\rightarrow\begin{bmatrix}1&1&1&1\\0&1&-2&3\\0&\cancel{3}&-\cancel{6}&\cancel9\\0&3&4&-1\\0&0&0&0\end{bmatrix}\\&\rightarrow\begin{bmatrix}\boxed1&1&1&1\\&\boxed1&-2&3\\&&\boxed{10}&10\\&&&0\\&&&0\end{bmatrix} \Rightarrow C(A^{T})=Span\left\{\begin{bmatrix}0\\2\\4\\1\\6\end{bmatrix},\begin{bmatrix}0\\1\\1\\1\\3\end{bmatrix},\begin{bmatrix}0\\4\\10\\1\\2\end{bmatrix}\right\}\end{aligned}$$
$$\begin{aligned}&(3)N(A)\\&Ax=0\Rightarrow\begin{bmatrix}0&2&0&3&0\\0&0&2&-1&0\\0&0&0&0&10\\0&0&0&0&0\end{bmatrix}\begin{bmatrix}x_1\\\vdots\\x_5\end{bmatrix}=0\Rightarrow\begin{cases}x_1,x_4\in\mathbb{R}\\x_2=-\frac32x_4\\x_3=\frac12x_4\\x_5=0\end{cases}\end{aligned}$$
$$\begin{aligned}\Rightarrow x=k_1\begin{bmatrix}1\\0\\0\\0\\0\end{bmatrix}+k_2\begin{bmatrix}0\\-3/2\\1/2\\1\\0\end{bmatrix}(k_1,k_2\in\mathbb{R})\end{aligned}$$

$(4)N(A^T)$
$$\begin{aligned}\\A^{T}y=0&\Rightarrow\begin{bmatrix}1&1&1&1\\&1&-2&3\\&&10&-10\\&&&0 \\&&&0\end{bmatrix}\begin{bmatrix}y_1\\y_2\\y_3\\y_4\end{bmatrix}=0\\&\end{aligned}$$
$$\begin{aligned}\Rightarrow\begin{cases}y_1=-y_4\\y_2=-y_4\\y_3=y_4\\y_4\in R\end{cases}\Rightarrow y=k_{0}\begin{bmatrix}-1\\-1\\1\\1\end{bmatrix},k_{0}\in R\end{aligned}$$

$$\begin{aligned}&(b)Ax=b\text{ 时 利用高斯消元化简增广矩阵(略)}\\&\text{令出一特解 }x_{p}=\left[1~-5~~1~3~1\right]^{T}\\&x=x_{p}+x_{n}=\begin{bmatrix}1\\-5\\1\\3\\1\end{bmatrix}+k_{1}\begin{bmatrix}1\\0\\0\\0\\0\end{bmatrix}+k_{4}\begin{bmatrix}0\\-3/2\\1/2\\1\\0\end{bmatrix}\quad k_{1},k_{4}\in\mathbb{R}\end{aligned}$$


$$\begin{aligned}
\textbf{五、}\text{令 }~~~X&=\begin{bmatrix}a&b\\c&d\end{bmatrix},\\\text{则 XA}&=\begin{bmatrix}a&b\\c&d\end{bmatrix}\begin{bmatrix}1&1\\0&2\end{bmatrix}=\begin{bmatrix}a&a+2b\\c&c+2a\end{bmatrix}\\AX&=\begin{bmatrix}1&1\\0&2\end{bmatrix}\begin{bmatrix}a&b\\c&d\end{bmatrix}=\begin{bmatrix}a+c&b+d\\2c&2d\end{bmatrix}\\T(x)&=XA+AX=\begin{bmatrix}2a+c&a+3b+d\\3c&c+4d\end{bmatrix}\\&=(2a+c)V_1+(a+3b+d)V_2+(3c)V_3+(c+4d)V_4\\
\end{aligned}$$

$$\begin{aligned}\\T&(\begin{bmatrix}a&b\\c&d\end{bmatrix})=(V_1~V_2~V_3~V_4)\begin{pmatrix}2a+c\\a+3b+d\\3c\\c+4d\end{pmatrix}\end{aligned}$$

$$\begin{aligned}\text{六、}&\left(A+B\right)^{2}\\&=(A+B)(A+B)=A^{2}+AB+BA+B^{2}=A+B\\&\because A^{2}=A,B^{2}=B\\&\therefore AB+BA=0  \quad\dots\dots\dots①\\&B(AB+BA)=BAB+B^{2}A=(BA)B+B^{2}A=-AB^{2}+B^{2}A=0\\&又\because B^{2}=B\\&\therefore-AB^{2}+B^{2}A=-AB+BA=0\quad\dots\dots\dots②\\&\text{联立①②}\begin{cases}AB+BA=0\\-AB+BA=0\end{cases}\Rightarrow AB=0,\text{得证}\end{aligned}$$
七、
$$\begin{aligned}&(a)(AB)^{2}=(AB)(AB)=\begin{bmatrix}8&0&-4\\-\frac{3}{2}&9&-6\\-2&0&1\end{bmatrix}\begin{bmatrix}8&0&-4\\-\frac{3}{2}&9&-6\\-2&0&1\end{bmatrix}\\&=\begin{bmatrix}72&0&-36\\-\frac{27}{2}&81&-54\\-18&0&9\end{bmatrix}\\\end{aligned}$$
$$\begin{aligned}&(b)\\ &\quad\begin{aligned}&(AB)^{2}=9(AB)\\&R(A)\geq R(AB)=2\Rightarrow R(A)=2,同理R(B)=2\\&A\text{行满秩, 令}XA=I_{2},X\text{为A左逆}\\&B\text{列满秩, 令}BY=I_{2},Y\text{为B右逆}\\&\therefore BA=(XA)(BA)(BY)=X(AB)^{2}Y=9XABY=9I\end{aligned}\end{aligned}$$
