# Covariance & Correlation
They are two statistical measures used to determined relationship between 2 varaible. Both are used to 
understand how chagnes in one variable are associated with changes in another. 

| **Aspect**         | **Covariance**                                                       | **Correlation**                                                                |
| ------------------ | -------------------------------------------------------------------- | ------------------------------------------------------------------------------ |
| **Definition**     | Measures how two variables change **together**                       | Measures **strength and direction** of a linear relationship between variables |
| **Symbol**         | $\text{Cov}(X, Y)$                                                   | $r$ or $\rho$ (rho)                                                            |
| **Formula**        | $\text{Cov}(X, Y) = \frac{1}{n} \sum (x_i - \bar{x})(y_i - \bar{y})$ | $r = \frac{\text{Cov}(X, Y)}{\sigma_X \cdot \sigma_Y}$                         |
| **Range**          | $-\infty$ to $+\infty$                                               | -1 to +1                                                                       |
| **Interpretation** | Hard to interpret directly; depends on units                         | Easy to interpret (e.g., r = 0.8 = strong positive relationship)               |
| **Unit**           | Product of units of X and Y (e.g., cm·kg)                            | Unitless                                                                       |
| **Relationship**   | Only tells **direction** (positive/negative)                         | Tells **direction and strength**                                               |

![974ce4914dde5a5c9b9f1394fb8f37abafc8493b](https://github.com/user-attachments/assets/53e6d6fb-e1fd-4dd3-a57a-6bb8a102f627)


## Pearson Correlation and Spreaman Correlation
| **Feature**                | **Pearson Correlation**                   | **Spearman Correlation**                                           |
| -------------------------- | ----------------------------------------- | ------------------------------------------------------------------ |
| **Symbol**                 | $r$                                       | $\rho_s$ or Spearman’s $r_s$                                       |
| **Type of Relationship**   | Measures **linear** relationship          | Measures **monotonic** relationship (can be nonlinear but ordered) |
| **Data Type**              | Requires **interval or ratio** scale data | Can use **ordinal, interval, or ratio** data                       |
| **Assumes Normality?**     | Yes (data should be normally distributed) | No (non-parametric test)                                           |
| **Sensitive to Outliers?** | Yes                                       | Less sensitive                                                     |
| **Calculation**            | Based on **raw values**                   | Based on **ranks** of the data                                     |
| **Interpretation Range**   | -1 to +1                                  | -1 to +1                                                           |

![0_jaBjgiUZuTEydu1D](https://github.com/user-attachments/assets/95f732af-c375-4c25-8892-4df8fa655658)
