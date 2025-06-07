# Probability Distribution

Probability distribution describe how probabilities are distributed over the value of random variable. 

## Probability Mass Function (PMF): 
Used for discrete random variable. 

## Probability Density Function (PDF): 
Used for continuous random variable

## Cumulative Distribution Function (CDF): 

| **Feature**                 | **PMF (Probability Mass Function)**                                                  | **PDF (Probability Density Function)**                                              | **CMF (Cumulative Distribution Function)**                                            |
| --------------------------- | ------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- |
| **Applies to**              | Discrete random variables                                                            | Continuous random variables                                                         | Both discrete and continuous random variables                                         |
| **Definition**              | Gives the probability that a discrete random variable is exactly equal to some value | Describes the relative likelihood of a continuous variable to take a specific value | Gives the probability that a random variable is less than or equal to a certain value |
| **Notation**                | $P(X = x)$                                                                           | $f(x)$                                                                              | $F(x) = P(X \leq x)$                                                                  |
| **Output value**            | Probability (between 0 and 1)                                                        | Not a probability itself; area under the curve gives probability                    | Probability (between 0 and 1)                                                         |
| **Summation / Integration** | $\sum_x P(X = x) = 1$                                                                | $\int_{-\infty}^{\infty} f(x) \, dx = 1$                                            | $\lim_{x \to \infty} F(x) = 1$                                                        |
| **Value at a point**        | Gives exact probability for a point                                                  | Probability at a point is 0; only intervals have non-zero probabilities             | Gives cumulative probability up to that point                                         |
| **Graph shape**             | Discrete bars at specific points                                                     | Smooth curve over a range of values                                                 | Step-like for discrete; smooth S-curve for continuous                                 |
| **Example**                 | Tossing a die: $P(X = 3) = \frac{1}{6}$                                              | Normal distribution: Bell curve                                                     | $P(X \leq 3)$ from PMF or PDF                                                         |


