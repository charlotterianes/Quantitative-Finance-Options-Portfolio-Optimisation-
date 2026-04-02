# Quantitative-Finance-Options-Portfolio-Optimisation-
Options Pricing &amp; Portfolio Optimisation 

- mynormcdf(x): approximate the standard normal cumulative distribution function (CDF) using a polynomial approximation.
- option_BS_c(S0, K, r, sigma, T): compute the Black-Scholes price of a European call option.
- CRR_Euro_Call(S0, K, r, sigma, T, N, isRound=False, dp=4): price a European call option with the Cox-Ross-Rubinstein binomial tree.
- CRR_Euro_Put(S0, K, r, sigma, T, N, isRound=False, dp=4): price a European put option with the CRR binomial tree.
- CRR_Amer_Call(S0, K, r, sigma, T, N, isRound=False, dp=4): price an American call option with the CRR binomial tree and early exercise.
- CRR_Amer_Put(S0, K, r, sigma, T, N, isRound=False, dp=4): price an American put option with the CRR binomial tree and early exercise.
- TriTree_Euro_Call(S0, K, r, sigma, T, N, isRound=False, dp=4): price a European call option using a trinomial tree.
- FDExplicit_Euro_Call(S0, K, r, sigma, T, M, N, isRound=False, dp=4): solve a European call option via explicit finite differences (used for small step sizes) 
- FDImplicit_Euro_Call(S0, K, r, sigma, T, M, N, isRound=False, dp=4): solve a European call option via implicit finite differences (used for larger time steps and unconditionaly stability) 

Cox-Ross-Rubinstein (CRR) versus Finite Difference Method (FDM)
- CRR is used for vanilla / American options
- FDM is used for complex path-dependent / Exotic options 
