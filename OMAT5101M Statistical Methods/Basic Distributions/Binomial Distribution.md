- Probability of $k$ Successes in $n$ trials
$$P(S_n=k)=\binom{n}{k}p^kq^{(n-k)} $$
$$E[S_n]=np
\qquad\text{and}\qquad 
Var(S_n)=npq
$$
- We can approximate the Binomial Distribution via the [[Normal Distribution]]
$$Bin(n,p)\approx N(np, npq)$$
- But we require that the sample size $n$ is large enough and that the probability of success $p$ is not too small or too large
$$np\ge 10,nq\ge10
\qquad\text{or}\qquad
npq\ge 5$$
- We can approximate the Binomial Distribution via the [[Poisson Distribution]] as long as the probability of success is very small and we have a large number of trials
$$Bin(n,p)\approx Pois(np)$$
- For either approximation, we should use continuity corrections by extending the bounds of the inequalities by 0.5 as appropriate, it should always make the bounded space larger