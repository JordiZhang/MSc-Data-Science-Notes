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
Let $U_1,...,U_n$ be independent random variables with uniform distribution $[0,1]$. Arranging the values in increasing order, we obtain order statistics. If we choose a random U, the probability that this U is the $kth$ value in the order, is distributed according to:
$$f_{(k)}(x)=n\binom{n-1}{k-1}x^{k-1}(1-x)^{n-k}$$