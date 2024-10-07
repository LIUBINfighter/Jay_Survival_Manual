线代23秋期中试题 en 发布版

1.(15 points, 3 points each) Multiple Choice. Only one choice is correct.

(1)Suppose that $\alpha_1,\alpha_2,\alpha_3$ are a basis for nullspace of a matrix $A,N(A)$. Which of the following lists of vectors is also a basis for $N(A)$?

(A)$\alpha_{1}+\alpha_{2}-\alpha_{3}, \alpha_{1}+\alpha_{2}+5\alpha_{3}, 4\alpha_{1}+\alpha_{2}-2\alpha_{3}$.

(B)$\alpha_{1}+2\alpha_{2}+\alpha_{3}, 2\alpha_{1}+\alpha_{2}+2\alpha_{3}, \alpha_{3}+\alpha_{1}+\alpha_{2}$,

(C)$\alpha_{1}+\alpha_{2}, \alpha_{1}+\alpha_{2}+\alpha_{3}$.

(D)$\alpha_{1}-\alpha_{2}, \alpha_{2}-\alpha_{3}, \alpha_{3}-\alpha_{1}$.



(2)Which of the following statements is correct?

(A) If the columns of $A$ are linearly independent, then $A\mathbf{x}=\mathbf{b}$ has exactly one solution for every b.

(B) Any $5\times7$ matrix has linearly dependent columns.

(C) If the columns of a matrix $A$ are linearly dependent, so are the rows.

(D) The column space and row space of a $10\times12$ matrix may have different dimensions.



(3)Let
$$\left.\alpha_{1}=\left[\begin{array}{r}1\\4\\1\end{array}\right.\right],\:\alpha_{2}=\left[\begin{array}{r}2\\1\\-5\end{array}\right],\alpha_{3}=\left[\begin{array}{r}6\\2\\-16\end{array}\right],\:\beta=\left[\begin{array}{r}2\\t\\3\end{array}\right].$$
$\beta$ can be written as a linear combination of $\alpha_1,\alpha_2,\alpha_3$ if $t= ()$

(A)1.

(B)3.

(C)6.

(D)9.



(4) Which of the following statements is correct?

(A) Suppose that $EA=B$ and $E$ is an invertible matrix, then the column space of $A$and the column space of $B$ are the same.

(B) Let $A$ be a $n\times n$ matrix with rank 1, then $A^n=cA$, where $n$ is a positive integer and $c$ is a real number.

(C) Let $A,B$ be symmetric matrices, then $AB$ is symmetric.

(D) If $A$ is of full row rank, then $Ax=0$ has only the zero solution.

<hr style="border: 1px solid black;">

(5)Let A and B be two $n \times n$ matrices. If A is a non-zero matrix and AB = 0, then

(1)$BA=0$

(2)$B=0$

(3)$(A+B)(A-B)=A^2-B^2$

(4)$\text{rank } B<n$.

<hr style="border: 1px solid black;">

2.$\left(25\text{ points, 5 points each) Fill in the blanks.}\right.$

(1)Denote the vector space of $7\times7$ real matrices by $M_{7\times7}(\mathbb{R})$, and let $W$ be the subspace of $M_{7\times7}(\mathbb{R})$ consisting of skew-symmetric real matrices, then dim $W=\underline{\quad\quad\quad}.$
$\text{A matrix } A \text{ is called skew symmetric if } A^{T}= - A.$

(2)$\operatorname{Let}A,B$ be two $n\times n$ invertible matrices. Suppose the inverse of $\left[\begin{array}{ccc}A&C\\O&B\end{array}\right]$is$\left[\begin{array}{cc}A^{-1}&D\\O&B^{-1}\end{array}\right]$，where $O$ is the $n\times n$ zero matrix. Then $D=\underline{\quad\quad\quad}.$

(3)Let $A=\left[\begin{array}{cccc}a&1&1&1\\1&a&1&1\\1&1&a&1\\1&1&1&a\end{array}\right]$with $rank(A)<4$. Then $a =\underline{\quad\quad\quad}.$ 

(4)Consider the system of linear equations
$$\begin{aligned}&A\mathbf{x}=\mathbf{b}:\left\{\begin{array}{cccc}x&+&2y&=&1\\x&-&y&=&2\\&&y&=&-1.\end{array}\right.\\\end{aligned}$$
The least-squares solution for the system is$\underline{\quad\quad\quad}.$

(5)
Let $H$ be the subspace of $R^3$ be defined as follows:
$$H=\left\{\left[\begin{array}{c}x_1\\x_2\\x_3\end{array}\right]\Bigg| x_1+2x_2+x_3=0\right\}.$$
A **unit** vector orthogonal to $H$ is $\underline{\quad\quad\quad}.$

<hr style="border: 1px solid black;">

3.(24 points) Consider the following $4\times5$ matrix A with its reduced row echelon form R:
$$\left.A=\left[\begin{array}{rrrrr}1&2&*&1&*\\0&1&*&1&*\\-1&1&*&3&*\\2&0&*&1&*\end{array}\right.\right],\:R=\left[\begin{array}{rrrr}1&0&1&0&3\\0&1&2&0&1\\0&0&0&1&1\\0&0&0&0&0\end{array}\right]$$
(a) Find a basis for each of the four fundamental subspaces of $A.$
(b) Find the third column of matrix $A.$

<hr style="border: 1px solid black;">

4.(15points)Let
$$\left.A=\left[\begin{array}{ccc}1&-1&-1\\2&a&1\\-1&1&a\end{array}\right.\right],\:B=\left[\begin{array}{ccc}2&2\\1&a\\-a-1&-2\end{array}\right].$$
For which value(s) of $a$, the matrix equation $AX=B$ has no solution, a unique solution, or infinitely many solutions? Where $X$ is a $3\times2$ matrix. Solve $AX=B$ if it has at least one solution.

<hr style="border: 1px solid black;">

5.(15 points) Let $M_2\times2(\mathbb{R})$ be the vector space of $2\times2$ real matrices. Let
$$A=\left[\begin{array}{rr}1&0\\0&-1\end{array}\right],\:B=\left[\begin{array}{rr}0&1\\0&0\end{array}\right],\:C=\left[\begin{array}{rr}0&0\\1&0\end{array}\right].$$
Consider the map
$$T:M_{2\times2}(\mathbb{R})\to\mathbb{R}^3,\:T(X)=\left[\begin{array}{c}tr(A^TX)\\tr(B^TX)\\tr(C^TX)\end{array}\right],$$
for any $2\times2$ real matrix $X$, where $tr(D)$ denotes the trace of a matrix $D.$
The trace of an $n\times n$ matrix D is defined to be the sum of all the diagonal entries of D, in other words,
$$tr(D)=d_{11}+d_{22}+\cdots+d_{nn}.$$

(a) Show that $T$ is a linear transformation.

(b) Find the matrix representation of $T$ with respect to the ordered basis
$$\left.v_{1}=\left[\begin{array}{cc}1&0\\0&0\end{array}\right.\right],\:v_{2}=\left[\begin{array}{cc}0&0\\0&1\end{array}\right],\:v_{3}=\left[\begin{array}{cc}0&1\\1&0\end{array}\right],\:v_{4}=\left[\begin{array}{cc}0&1\\-1&0\end{array}\right]$$
$\operatorname{for}M_{2\times2}\left(\mathbb{R}\right)$and the standard basis
$$\left.e_{1}=\left[\begin{array}{c}1\\0\\0\end{array}\right.\right],\:e_{2}=\left[\begin{array}{c}0\\1\\0\end{array}\right],\:e_{3}=\left[\begin{array}{c}0\\0\\1\end{array}\right]$$
for $\mathbb{R}^3.$

(c) Can we find a matrix $X$ such that $T(X)=\left[\begin{array}{c}1\\-2\\1\end{array}\right]?$ If yes, please find one such matrix. Otherwise, give an explanation.

<hr style="border: 1px solid black;">

6.(6 points) Let $A$ be an $m\times n$ matrix, $B$ be an $m\times p$ matrix, and $C$ be an $q\times p$ matrix. Show that
$$\left.\mathrm{rank~}\left[\begin{array}{cc}A&B\\O&C\end{array}\right.\right]\geq\mathrm{rank~}A+\mathrm{rank~}C,$$
where $O$ is the $q\times n$ zero matrix.
