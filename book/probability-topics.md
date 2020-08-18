# Probability Topics

 * Basics of probability
    * Probability models
        * Probability denstiy functions
        * Classic distributons
            * Bernouli 
            * Binomial
            * Poisson
            * Gaussian
            * Chi-Square
            * Exponential family
        * Multivariate distributions
            * Independence
            * Covariance
            * Conditional distributions
            * Marginal distributions
            * Graphical Models
            * Copula
        * Information theory
            * Entropy
            * Mutual information
            * KL divergence
            * cross entropy
        * Divergences
            * KL Divergence
            * Fisher distance
            * Optimal Transport
            * Hellinger distance
            * f-divergences
            * Stein divergence
        * Implicit probabity models
            * Simulators
            * Probabilistic Programming
                * pyro
                * pyprob
    * Likelihood function
    * [Axioms of probability](https://en.wikipedia.org/wiki/Probability_axioms)
        * [Probability Space](https://en.wikipedia.org/wiki/Probability_space)
    * Transformation properties
        * Change of variables
            * Propagation of errors
        * Reparameterization
    * Bayes Theorem
        * Subjective priors
        * Emperical Bayes
        * Jeffreys' prior
        * Unfiform priors
        * Reference Priors
        * Transformation Properties
    * Convolutions and the Central Limit Theorem
        * Binomial example
        * Convolutions in Fourier domain



Some references:
 * [Probability and Statistics](https://cims.nyu.edu/~cfgranda/pages/DSGA1002_fall17/index.html)
 * [Inference and Representation](https://inf16nyu.github.io/home/)
 * [Big Data 2015](https://www.vistrails.org/index.php/Course:_Big_Data_2015)
 * [Machine Learning](https://davidrosenberg.github.io/ml2017/#resources)
     * [PRML](https://github.com/cranmer/PRML)
 * [Stanford Prob](http://cs229.stanford.edu/section/cs229-prob.pdf) 

 ```{math}
:label: autoregressive
p(x_1, \dots, x_T) = \prod_{t=1}^T p(x_t \mid x_{<t})
```

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">The 10 most helpful *free* online machine learning courses, via <a href="https://twitter.com/chipro?ref_src=twsrc%5Etfw">@chipro</a><br><br>Full thread: <a href="https://t.co/RUcG2AL1uC">https://t.co/RUcG2AL1uC</a><a href="https://twitter.com/hashtag/MondayMotivation?src=hash&amp;ref_src=twsrc%5Etfw">#MondayMotivation</a> <a href="https://t.co/Fd3sN2u7UV">pic.twitter.com/Fd3sN2u7UV</a></p>&mdash; MIT CSAIL (@MIT_CSAIL) <a href="https://twitter.com/MIT_CSAIL/status/1295391687783718914?ref_src=twsrc%5Etfw">August 17, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>