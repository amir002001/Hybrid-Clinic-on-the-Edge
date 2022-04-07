# noise and outlier removal

Date: 2022-04-02

## Description
Data can be noisy. When you have a small (relative to population size), random sample of the population, especially noisy population, it can be quite a challenge, if not impossible, to build a model that would generalize well.

Imagine you built a simple linear model that performed poorly on your data. Then, you decided to compute studentized residuals and remove all the observations that fall out of a certain scope. As a result, your model fits the data far better. Finally, you put it into production and the fit is a nightmare.

Noisy data is not a rare occurrence and it can greatly influence your findings. Knowing how to recognize and how to deal with it is important for any accurate finding.

## Tags


## Related Topics
https://towardsdatascience.com/how-to-deal-with-outliers-in-a-noisy-population-736d7a048199