$$f(x)=\lambda e^{-\lambda x}$$
$$E[X]=\frac{1}{\lambda},\qquad Var(X)=\frac{1}{\lambda^2}, \qquad E[X^k]=\frac{k!}{\lambda^k}$$
# Sum of Exponential Variables
The sum of variables each with an exponential distribution, the resulting distribution is a convolution of both. In general, the sum of $n$ such variables with same rate $\lambda$, has density:
$$f_n(x)=\frac{\lambda^nx^{n-1}e^{-\lambda x}}{(n-1)!}\qquad (x>0)$$
This is a special case of the Gamma distribution with shape $\alpha>0$ and rate $\lambda>0$.
# Distribution of the Minima
Say we have 2 random exponential variables. We want to find the distribution of the minimum of both, i.e. $Y=min\{X_1,X_2\}$ . $Y$ will have an exponential distribution with parameter $\lambda = \lambda_1 + \lambda_2$. 
$$P(Y>x)=P(X_1>x, X_2>x)=P(X_1>x)\cdot P(X_2>x)=e^{-(\lambda_1+\lambda_2)x}$$
Generalizing to $n$ random variables with same rate $\lambda$, we get that 
$$Y\sim Exp(n\lambda)$$