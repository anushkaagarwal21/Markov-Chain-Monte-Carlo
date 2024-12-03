The Markov Chain Monte Carlo (MCMC) method is an iterative sampling method based on the familiar Bayes' theorem, given by: $p(y,|x)=\\frac{p(x|y)p(y)}{p(y)}$. The algorithm includes-

1. Drawing trial point from proposal distribution, $P(X_{trial}|X_{s-1})$

2. Accept the trial point with the probability min $[p(X_{trial})|p(X_{s-1}),1]$

3. If the trial point is accepted, then set $X_s = X_{trial}$ otherwise set $X_s = X_{s-1}$

Here the likelihood is-


![likelihood_g](https://github.com/user-attachments/assets/cd0c3918-85b9-4741-a7da-8a51c8cba73a)
