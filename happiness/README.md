The dataset 'happiness.csv' contains a wealth of information examining the factors contributing to happiness across different countries and years. In analyzing this data, we can derive insights into trends, correlations, and anomalies that may inform future studies or policy decisions.

### Summary of Data

The dataset consists of multiple variables that contribute to the assessment of happiness, including:

- **Life Ladder**: A measure of perceived quality of life.
- **Log GDP per capita**: Economic measure indicating wealth.
- **Social support**: Indicator of perceived community support.
- **Healthy life expectancy at birth**: Health-related measure.
- **Freedom to make life choices**: Indicator of personal agency.
- **Generosity**: Measure of charitable giving.
- **Perceptions of corruption**: Indicator of trust in institutions.
- **Positive and Negative affect**: Measures of emotional well-being.

This dataset captures 2363 observations across 165 countries from the years 2005 to 2023, with an average year around 2014.76.

### Key Insights

#### Trends

1. **Overall Happiness (Life Ladder)**:
   - The mean Life Ladder score is around **5.48** on a scale likely from 0 to 10, with a range spanning from **1.281** to **8.019**. This suggests variations in happiness levels, with a considerable number of countries exhibiting lower scores.

2. **Economic Correlation**:
   - The correlation between **Log GDP per capita** and **Life Ladder** is significantly high (**0.78**). Higher economic status typically correlates with increased happiness, confirmed by the dataset. Countries with higher GDP per capita tend to report better life satisfaction.

3. **Social Support**:
   - The **Social support** variable also shows a strong relationship with happiness (correlation of **0.72** with Life Ladder), indicating that community bonds greatly affect well-being. Investment in social programs could yield happiness increases.

4. **Freedom and Happiness**:
   - **Freedom to make life choices** displays a notable positive correlation (**0.54**) with Life Ladder. This highlights the importance of personal freedoms and agency in happiness, suggesting that more liberal governance and policies that embrace individual choice may enhance life satisfaction.

5. **Corruption's Impact**:
   - The correlation between **Perceptions of corruption** and **Life Ladder** is negatively strong (**-0.43**). Countries perceived as more corrupt tend to have lower happiness scores, underscoring the need for transparency and governance reforms in relation to citizen satisfaction.

#### Outliers and Anomalies

- **Generosity**: The average score is very low (**0.0001**), indicating that even countries with higher happiness may struggle with charitable behaviors. Instances of very low generosity could indicate cultural tendencies or economic pressures impacting philanthropy.
- **Health & Life Expectancy**: While the mean **Healthy life expectancy at birth** is **63.40**, outliers may reveal regions with significantly lower averages due to healthcare access disparities, affecting happiness.

### Further Analysis Suggestions

1. **Clustering Analysis**:
   - **K-means clustering** on the relevant factors could divide countries into clusters by happiness. This analysis could expose diverse correlational profiles among countries, allowing for targeted policy implementation where interventions could improve regional happiness levels.

2. **Anomaly Detection**:
   - Implementing techniques like **Isolation Forest** or **DBSCAN** could uncover unexpected deviations in happiness levels based on specific socio-economic factors, allowing researchers to investigate surprising trends.

3. **Time Series Analysis**:
   - Given the time variation in the dataset, a **time series analysis** could reveal trends over the years in life satisfaction, revealing how events (e.g., economic crises or health pandemics) influenced happiness differently across regions.

### Implications for Future Decisions

Understanding the trends in happiness concerning economic and social factors has significant implications for policymakers. As resilience amid crises (like the COVID-19 pandemic) and long-term happiness are increasingly valued, governments could consider:

- Investing in healthcare and wellness programs to enhance life expectancy.
- Promoting social support networks to build community resilience.
- Ensuring transparency and reducing perceived corruption through policy reforms.
- Enabling individual freedoms through liberal policies to enhance happiness.

By aligning socio-economic policies with the findings from this data analysis, decision-makers can strive to create happier societies.

![correlation_heatmap.png](correlation_heatmap.png)
![Life Ladder_distribution.png](Life Ladder_distribution.png)
![Log GDP per capita_distribution.png](Log GDP per capita_distribution.png)
![year_distribution.png](year_distribution.png)