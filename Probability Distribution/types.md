# Type of Distribution

![images](https://github.com/user-attachments/assets/d8a843db-8eec-4e3e-a336-672b2a0ef81a)

| **Distribution Type**        | **Category** | **Description**                                                              | **Example**                                    | **Key Properties**                                                |
| ---------------------------- | ------------ | ---------------------------------------------------------------------------- | ---------------------------------------------- | ----------------------------------------------------------------- |
| **Binomial Distribution**    | Discrete     | Counts number of successes in fixed number of independent Bernoulli trials   | Tossing a coin 10 times and counting heads     | Two outcomes (success/failure), fixed trials $n$, probability $p$ |
| **Poisson Distribution**     | Discrete     | Counts number of events in a fixed interval of time or space                 | Number of emails received per hour             | Mean $\lambda$, models rare events, no fixed upper limit          |
| **Uniform (Discrete)**       | Discrete     | All outcomes are equally likely                                              | Rolling a fair die                             | Equal probability for each outcome                                |
| **Geometric Distribution**   | Discrete     | Number of trials until the first success                                     | Number of coin tosses until first head         | Memoryless property, probability $p$                              |
| **Hypergeometric**           | Discrete     | Like binomial, but without replacement                                       | Drawing cards from a deck without replacing    | Finite population, no replacement                                 |
| **Normal Distribution**      | Continuous   | Bell-shaped curve; most common natural distribution                          | Heights, test scores                           | Symmetrical, mean = median = mode, described by $\mu$, $\sigma$   |
| **Uniform (Continuous)**     | Continuous   | All intervals of the same length are equally likely                          | Random number between 0 and 1                  | Flat distribution, constant PDF                                   |
| **Exponential Distribution** | Continuous   | Models time between events in a Poisson process                              | Time between arrivals at a bus stop            | Skewed right, memoryless, rate parameter $\lambda$                |
| **Beta Distribution**        | Continuous   | Models probabilities over the interval \[0, 1], often used in Bayesian stats | Prior distribution in Bayesian inference       | Two shape parameters $\alpha$, $\beta$, flexible shapes           |
| **Gamma Distribution**       | Continuous   | Generalization of exponential; models waiting times                          | Total time for multiple Poisson events         | Shape $k$, rate $\theta$; skewed                                  |
| **Chi-Square Distribution**  | Continuous   | Special case of gamma; used in hypothesis testing                            | Chi-square tests in statistics                 | Skewed right, degrees of freedom $df$                             |
| **T-Distribution**           | Continuous   | Like normal but with heavier tails; used with small samples                  | Estimating a population mean when $n$ is small | Symmetric, converges to normal as sample size increases           |
| **F-Distribution**           | Continuous   | Ratio of two chi-square distributions                                        | ANOVA tests                                    | Skewed right, used to compare variances                           |
