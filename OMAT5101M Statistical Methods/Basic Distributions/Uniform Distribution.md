$$
f(x)=\begin{cases}
	\frac{1}{b-a} & a\leq x\leq b\\
	0 & \text{otherwise}
\end{cases}
$$
$$E[X]=\frac{a+b}{2}, \qquad Var(X)=\frac{(b-a)^2}{12}$$
# Probability Integral Transform
To sample from any probability distribution, we can instead sample values from the uniform distribution $[0,1]$. Using these values we plug them into the inverse of the cumulative probability distribution to obtain a value for x. Thus this value of x is sampled from its probability distribution.
![[Probability Integral Transform.png]]
# Order Statistics
Let $U_1,...,U_n$ be independent random variables with uniform distribution $[0,1]$. Arranging the values in increasing order, we obtain order statistics, $U_{(1)}<U_{(2)},...,U_{(n)}$. If we choose a random U, the probability density that this $U_{(k)}$ is the $kth$ value in the order, is distributed according to:
$$f_{(k)}(x)=n\binom{n-1}{k-1}x^{k-1}(1-x)^{n-k}\qquad (0\leq x\leq 1 )$$
In particular, the densities for the minimum and maximum are:
$$f_{(1)}(x)=n(1-x)^{n-1},\qquad f_{(n)}(x)=nx^{n-1}\qquad (0\leq x\leq 1)$$
The Expectation value is given by:
$$E(U_{(k)})=\frac{k}{n+1}$$
In particular,
$$E(U_{(1)})=\frac{1}{n+1},\qquad E(U_{(n)})=\frac{n}{n+1}$$