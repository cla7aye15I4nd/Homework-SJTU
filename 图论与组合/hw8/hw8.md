## Problem2

$$
\begin{equation}
f_{n,k}=\left\{
	\begin{aligned}
		& \sum_{i=1}^{n-k+1}\binom{n-1}{i-1}(i-1)!f_{n-i,k-1} && k \not=0\\
		& [n=0] && k = 0
	\end{aligned}
\right.
\end{equation}
$$

$$f_{n,k}=f_{n,k-1}+(n-1)f_{n-1,k}$$

$f_{n,1}=(n-1)!$

$f_{n,2}=\sum_{i=1}^{n-1}\binom{n-1}{i-1}(i-1)!f_{n-i,1}=(n-1)!\sum_{i=1}^{n-1}\frac 1 {i}$

## Problem3

