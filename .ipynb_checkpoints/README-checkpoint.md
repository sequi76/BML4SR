# Bayesian ML for scientific research
Learning to propose, infer and test probabilistic models that describe systems to extract their relevant info

Ezequiel Alvarez (sequi@unsam.edu.ar)<br>
February 3rd - February 7th 2025<br>
2PM - 3PM Theory <br>
3PM - 4.30PM Hands-on practice <br>
ICASU Seminar room @ <a href="https://icasu.illinois.edu/">ICASU, Illinois University</a><br>


# Important preparation-info for the course:

## Questions, comments, videos, blogs

Sign in to the Slack channel of the course and put all your questions and comments here!
<br>
<br>
<a href='https://join.slack.com/t/bayesianmachi-o3n8107/shared_invite/zt-2y2vch1yv-7FHfuUOdqy3nUBsNLaOOHg'>``Go to Slack channel``</a>

## Software

It is important to prepare your laptop, computer, or remote server in order to be able to participate in the hands-on part of the course. Here a few comments about this:

- It is better if you have a Unix system on your computer (Linux, MacOS).  Windows is OK as long as you can run Python in it, and solve eventual problems with it.
- Install the following packages, if possible in the indicated versions when shown:
  - pystan:                    3.10.0
  - arviz:                     0.19.0
  - nest-asyncio               1.6.0
  - pandas, numpy, scipy, matplotlib, mpltern, ternary
  
- The above packages work correctly -at least- in ``Python 3.10.14``.  You can use ``conda`` to emulate an environment in which you install Python in any specific version, and then install the above packages in the indicated versions.
- Test that the notebook ``Hello_World_STAN.ipynb`` (see above!) works correctly in your computer.... and we are all set with software!
## Hardware

- Any normal laptop is OK.  In the 5th lecture your laptop may feel better if you have a server where to run the Python notebooks, but don't worry if you don't have it, we adapt the notebooks.

## Readings

- Give it a read to <a href='https://en.wikipedia.org/wiki/Bayes%27_theorem'>Bayes' Theorem</a>, and/or watch a <a href='https://www.youtube.com/watch?v=cqTwHnNbc8g'>nice video</a>!
- It would be better if you have some knowledge about the following distributions:
  - <a href="https://en.wikipedia.org/wiki/Normal_distribution">Normal or Gaussian</a> (of course that you know this one!)
  - <a href="https://en.wikipedia.org/wiki/Binomial_distribution">Bernoulli or Binomial</a>
  - <a href="https://en.wikipedia.org/wiki/Poisson_distribution">Poisson</a>
  - <a href="https://en.wikipedia.org/wiki/Multinomial_distribution">Multinomial</a>
  - <a href="https://en.wikipedia.org/wiki/Exponential_distribution">Exponential</a>
  - <a href="https://en.wikipedia.org/wiki/Dirichlet_distribution">Dirichlet</a> (this is important, and conceptually difficult)

- We'll use ``STAN`` probabilistic language, you can have some fun reading in advance its <a href="https://mc-stan.org/docs/2_18/stan-users-guide/">User's guide</a>
- A nice introductory paper for the course could be <a href="https://arxiv.org/abs/2011.01808">Bayesian Workflow</a>
- Take a look at the <a href="https://github.com/sequi76/bml4sr/blob/main/bibliography.md">proposed bibliography</a>

