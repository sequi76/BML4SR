# Challenges

### Going beyond Gaussian mixtures

1. Consider the grades in a given career (let's think of numbers between 0 and 10).  We want to know whether there are two clusters of students with different distributions.  A Gaussian is not a suitable distribution, since it is not bounded.  Therefore, model that these two hypothetical clusters have their grades <a href="https://en.wikipedia.org/wiki/Beta_distribution" taget=beta>Beta-distributed</a>.
    1. Create the python notebook that creates such data and then
   infers its parameters
    2. Try inferring using a Gaussian mixture model, even though the data is Beta mixture.
       
2. Mixture of many Gaussians.
    1. Create a new notebook that addresses the problem of a mixture of $N=4$ Gaussians.  Create the mixture fractions $\pi_i$, the Gaussian parameters $\mu_i$ $\sigma_i$, and then create the data itself.  Choose parameters such that it is hard to recognize the Gaussians by just visualizing the data as a whole (verify it with a histogram of the data).
    2. Create the STAN model to extract the posterior for the parameters and run it!
    3. Think how could you address the problem of a mixture of $N$ Gaussians in case you don't know $N$ ?!

### Thinking Bayesianly

3. Think of a system that could be modeled as being sampled from a PDF.  Draw the Graphical Model of such a system.  Did you model it bottom-up?  Up-up?  Is there still room to unfold more the system and access to latent variables into which you could inject prior-info?
4. What is the probability of Harris winning the election, given that Trump won ?

