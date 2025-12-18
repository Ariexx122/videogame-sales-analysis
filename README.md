
## Video Game Sales Analysis: Regional Trends & Strategic Insights 🎮
This project performs a comprehensive analysis of historical video game sales across North America (NA), Europe (EU), and Japan (JP). The goal is to identify patterns that determine a game's success, such as platform lifecycles, genre popularity, and the impact of critic/user reviews, to inform a data-driven marketing strategy for the upcoming year.

### Key Insights & Achievements 📊
1. Platform Lifecycle Identification: Analyzed 30 years of data to identify PS4, PS3, X360, and Wii as the most profitable platforms, accurately mapping console lifecycles and peak profitability periods.
2. Correlation Myth-Busting: Statistically demonstrated that the correlation between user/critic ratings and total sales is nearly zero, suggesting that review-driven marketing may not be as effective as once believed.
3. Regional Market Strategy: Identified that while PS3 holds a balanced 21.7% market share across all regions, the X360 dominates in NA and EU but has a negligible 1.79% share in Japan, where Role-Playing games are significantly more impactful.
4. Statistical Validation: Used T-tests to prove that user preferences between Action and Sports genres are fundamentally different ($P-value \approx 1.45 \times 10^{-15}$), allowing for more granular customer targeting.

### Technologies Used 🛠️
1. Python: Main programming language.
2. Pandas & NumPy: Data cleaning, imputation of missing values (e.g., handling "TBD" and NaN in scores), and aggregation.
3. Matplotlib & Seaborn: Time-series visualizations, box plots for sales distribution, and genre popularity bar charts.
4. Scipy (Stats): Implementation of Levene’s test for variance and T-tests for hypothesis verification.

### Hypothesis Testing 🧪
The project involved rigorous statistical testing to validate assumptions:

1. Platform Ratings: Tested if average user ratings for Xbox One and PC were the same. Result: Failed to reject the null hypothesis (no significant difference).
   
3. Genre Ratings: Tested if average user ratings for Action and Sports genres differed. Result: Rejected the null hypothesis (significant difference found).

### How to Run 🚀
Clone this repository.

1. Ensure you have pandas, matplotlib, and scipy installed.

2. Open the Jupyter Notebook to view the step-by-step analysis and data visualizations.
