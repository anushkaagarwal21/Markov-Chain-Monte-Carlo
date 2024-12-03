The Markov Chain Monte Carlo (MCMC) method is an iterative sampling method based on the familiar Bayes' theorem, given by: P(A|B) = [P(B|A) * P(A)] / P(B). The algorithm includes-
Drawing trial point from proposal distribution, P(X_trial|X_s-1)
accept the trial point with the probability min[p(trial)/p(X_s-1),1)
if the trial point is accepted, then set X_s = X_trial otherwise set X_s = X_s-1

Here the likelihood is 
![likelihood_g](https://github.com/user-attachments/assets/cd0c3918-85b9-4741-a7da-8a51c8cba73a)
