## Q1 : For the suburb Altona, it is postulated that a typical property sells for 800,000 dollar. Use the data at hand to test this assumption. Is the typical property price really 800,000 dollar or has it increased? Use a significance level of 5%
 **Conclusion:**
- There is insufficient evidence to support the claim that the mean property price in Altona is greater than 800,000 dollar. This suggests that the observed data does not provide strong enough support to conclude an increase in the mean property price.The Wilcoxon Signed-Rank Test, which evaluates the median rather than the mean, indicates that the observed data does not strongly support an increase in the property price.
- **Non-Normal Distribution:**
 The earlier Shapiro-Wilk test showed that the property price data for Altona is not normally distributed. In such cases, the mean can be heavily influenced by outliers or skewed data, while the median provides a more robust measure of central tendency.
 The Wilcoxon Signed-Rank Test specifically evaluates the median differences, making the use of the median consistent with the statistical method applied.

## Q2 : For the year 2016, is there any difference in prices of properties sold in the summer months vs winter months? Consider months from October till March as winter months and the rest as summer months. Use a significance level of 5%.
**Conclusion:**
- Since the P-value (0.000125) is much less than 0.05, we reject the null hypothesis.
This indicates that there is a statistically significant difference in property prices between the summer and winter months.

**Seasonal Variation:**
The significant difference suggests that property prices vary meaningfully between the two seasons. This could be due to factors such as market demand, seasonal preferences, or changes in property availability.

**Practical Impact:**
If we can analyze market trends or advising on buying/selling strategies, this insight can help highlight the influence of seasonality on property prices.

**Non-Normality and Unequal Variance:**
The Mann-Whitney U test was appropriate here because the data for both seasons was not normally distributed (as determined by the Shapiro-Wilk test) and had unequal variances (per Levene's test).

## Q3 : For the suburb of Abbotsford, what is the probability that out of 10 properties sold, 3 will not have car parking? Use the column car in the dataset. Round off your answer to 3 decimal places.
 **Conclusion:**
 The probability of exactly 3 properties out of 10 having no car parking is relatively moderate at 26%. This means that there is a 26% chance that exactly 3 out of 10 properties selected will have no car parking. This suggests that while properties without car parking are not the majority, they are still fairly common in Abbotsford. This information could be useful for real estate professionals, potential buyers, or investors considering the availability and desirability of properties with car parking in the area.

## Q4 : In the suburb of Abbotsford, what are the chances of finding a property with 3 rooms? Round your answer to 3 decimal places.
 **Conclusion:**
 Among all properties in Abbotsford (56 in total), a significant portion (20 out of 56) consists of 3-room properties. This makes 3-room properties relatively common.
If you randomly select a property in Abbotsford, the chance of it having 3 rooms is approximately 35.7%.

## Q5 : In the suburb of Abbotsford, what are the chances of finding a property with 2 bathrooms? Round your answer to 3 decimal places.
  **Conclusion:**
 Among all properties (56 in total), a considerable portion (19 out of 56) has 2 bathrooms, making them relatively common but slightly less frequent than 3-room properties.
  If you randomly select a property in Abbotsford, the chance of it having 2 bathrooms is 33.9%.
