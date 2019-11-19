## Portfolio Optimisation in MATLAB - Summary

**Project description:** This  57 page (including full code apendix) dissertation was written in my final year of Mathematics at Nottingham Trent University with the mission to explore and analyse three methods of solving the Mean-Variance Markowitz portfolio optimisation problem. The methods explored were quadratic programming, the eﬃcient frontier and Monte Carlo simulations. Fully functional codes were produced in MATLAB for each one of these methods and each one was critically evaluated on its strengths and weaknesses relative to the others.

### 1. Quadratic Programming

The Mean-Variance Markowitz portfolio optimisation problem was initially modelled into a quatdratic format that would be "MATLAB friendly", in order to use quadratic programming to find two optimum weightings for an investor's assets in a given portoflio - one for the greatest mean return for the lowest
variance and one for a minimum overall variance with a desired mean return

### 2. The Efficient Frontier

Using MATLAB's pre-built "Financial Toolbox" to create a ```portfolio``` object and and utilise the premade ```BlueChipStocks``` dataset. Two separate models were constructed for the eﬃcient frontier method. The ﬁrst model allows the user to select optimal portfolios using a mean-variance efficient frontier with a deﬁned level of desired risk or return, whilst the second model allows an optimal portfolio to be chosen in such a way that the Sharpe Ratio is maximised.

<img src="images/dummy_thumbnailEF.jpg?raw=true"/>

### 3. Monte Carlo Simulation

The third method of selecting optimal portfolio weightings that was explored in this dissertation is the method of Monte Carlo Simulations - in which the data is re-sampled in order to best estimate the probability distribution. The method utilised three premade portfolios and  MATLAB's "Optimisation Toolbox" - allowing the use of ```for``` loops and deﬁned vectors and matrices.

<img src="images/dummy_thumbnailMC.jpg?raw=true"/>


### 4. Conclusion

From this evaluation, it is suggested that the method most applicable to real-life ﬁnancial and investment scenarios is the eﬃcient frontier due to its relative simplicity, versatility and ease of interpretation


