- Total Probability Rule 
$$P(A)=\sum^{n}_{i=1}P(A|B_{i})\cdot P(B_{i})$$
- Conditional Probability
$$P(A|B)=\frac{P(A\cup B)}{P(B)}$$
- Bayes' Theorem
$$P(A|B)=\frac{P(B|A)P(A)}{P(B)}$$
- Expectation Value
$$E[X]=\sum^{}_{x}xp(x)\text{ or }\int_{x}xp(x)dx$$
- Variance
$$Var(X)=E[(X-\mu)^2] = E[X^2]-\mu^2$$
- Covariance
$$Cov(X,Y)=E[(X-\mu_x)(Y-\mu_y)]=E[XY]-E[X]E[Y]$$
$$Cov(X_1+X_2,Y)=Cov(X_1,Y)+Cov(X_2,Y)$$
- Sum of Variances by using the covariance definition
$$Var(X+Y)=Var(X)+Var(Y)+2Cov(X,Y)$$
- Cauchy-Schwarz Inequality by considering $E[(tX+Y)^2]$ and noting that its always positive
$$E[XY]^2\le E[X^2]E[Y^2]$$
- Markov's Inequality, for $X\ge 0$, then for any $a>0$
$$E[X]\ge aP(X>a)$$
- Chebyshev's Inequality, for $X$ a random variable with mean $\mu$ and variance $\sigma^2$, then for any $k>0$, thus the probability that a random variable differs from the mean by more than $k$ standard deviations is bounded as $\frac{1}{k^2}$. 
$$P(|X-\mu|>k)\le \frac{\sigma^2}{k^2}\text{, or } P(|X-\mu|>k\sigma)\le \frac{1}{k^2}$$


