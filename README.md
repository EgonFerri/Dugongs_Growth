# Dugongs_Growth

<p align="center">
<img src="https://www.ideegreen.it/wp-content/uploads/2017/01/lamantini-2.jpg">
</p>


1 Bayes for dugongs

1.1 Illustrate the characteristics of the statistical model for dealing with the Dugong’s data.

1.2 Derive the corresponding likelihood function.

1.3 Write down the expression of the joint prior distribution of the parameters at stake and illustrate your suitable choice for the hyperparameters.

1.4 Derive the functional form (up to proportionality constants) of all full-conditionals.

1.4.1 α

1.4.2 β

1.4.3 γ

1.4.4 τ2

1.5 Which distribution can you recognize within standard parametric families so that direct simulation from full conditional can be easily implemented?

1.6 Using a suitable Metropolis-within-Gibbs algorithm simulate a Markov chain (T=10000) to approximate the posterior distribution for the above model.

1.7 Show the 4 univariate trace-plots of the simulations of each parameter.

1.8 Evaluate graphically the behaviour of the empirical averages I^t with growing t=1,...,T.

1.9 Provide estimates for each parameter together with the approximation error and explain how you have evaluated such error.

1.9.1 Point estimates

1.9.2 Approximation error

1.10 Which parameter has the largest posterior uncertainty? How did you measure it?

1.11 Which couple of parameters has the largest correlation (in absolute value)?

1.12 Use the Markov chain to approximate the posterior predictive distribution of the length of a dugong with age of 20 years.

1.13 Provide the prediction of a different dugong with age 30.

1.14 Which prediction is less precise?

2 Markov chain

2.1 Starting at time t=0 in the state X0=1 simulate the Markov chain with distribution assigned as above for t=1000 consecutive times

2.2 compute the empirical relative frequency of the three states in your simulation

2.3 repeat the simulation for 500 times and record only the final state at time t=1000 for each of the 500 simulated chains. Compute the 
relative frequency of the 500 final states. What distribution are you approximating in this way? Try to formalize the difference between this point and the previous point.

2.4 compute the theoretical stationary distribution π and explain how you have obtained it.

2.5 Is it well approximated by the simulated empirical relative frequencies computed in 2.6 and 2.7?

2.6 what happens if we start at t=0 from state X_0=2 instead of X_0=1?

