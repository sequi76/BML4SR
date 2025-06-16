# Challenges


### Going beyond a linear model
1. Consider a linear model for a specific problem and explore it a little bit further by analyzing the approximations in it. Now analyze if you can propose a new model (beyond linear) that could adapt to these features and therefore reduce the impact of the approximations.


### General problems

2. Gaia measures distance to stars through paralax.  It measures the distance to a given star $n$ times and then reports: the mean distance ($\mu_{rep}$), its standard deviation ($\sigma_{rep}$), and how many times it measured the distance ($n$).  However, sometimes because of the uncertainty in the measurements the reported mean distance ends up being negative, $\mu_{rep} < 0$ !!  Of course that this is not physical.  However, could we make a model to infer a probability distribution for the true $\mu_{true}$ and $\sigma_{true}$ ?

<i>Note: I found that the problem is entertaining and it looks addressable.  However, I could not claim that the statement itself is true in what has to do with Gaia data.  (<a href="https://astronomy.stackexchange.com/questions/26250/what-is-the-proper-interpretation-of-a-negative-parallax" target=gaia>Read some more here</a>)</i>

3. John usually rides a bicycle.  He has an odometer and measured that the first time he fell he had done 520 miles without falling since he started.  The second time he fell he had done 640 miles without falling.  Then he said to himself “I'm falling because I'm not paying enough attention to the route, from now on I'm going to pay more attention”.  And then the third time he fell he went 710 miles without falling.  To what extent could we say that he improved?

4. Consider the plane ticket's price.  For instance, at skyscanner.com one can simultaneously find prices of different companies at given dates.  Suppose (not fully impossible) that you can scrap one of these sites and have all the prices: all companies, all destinations, all dates.  Propose a model on how the algorithms work to set the price for each company.  If you are brave... also write it down in Stan!  How could you check if it makes sense?

