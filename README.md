# Excel_AB_Testing_Dashboard
A marketing dashboard completed in Excel using Pivot Tables and Charts to analyze the data.
## Marketing A/B Data Analysis
The owners of a marketing company have data they’ve acquired from their website to see which if a campaign they ran would be successful. They’ve provided the Marketing A/B Dataset from Kaggle, and we’ve asked to find insights into the data. The A group has been shown ads and the B group have been shown a PSA in place of the ad.
+ Question: Do ads increase conversions and is the campaign successful??
+ Question: How does ad exposure (frequency) affect conversion, and is there saturation?
+ Question: When do users convert most (by day and time)?

Data was provided by a [Kaggle link](https://www.kaggle.com/datasets/faviovaz/marketing-ab-testing)

## Dashboard:
![AB_test_ss.jpg](https://github.com/patrick-curry/Excel_AB_Testing_Dashboard/blob/main/AB_test_ss.jpg)

## Process:
- Data Validation:
Reviewed the dataset for missing values, inconsistencies, and anomalies to ensure data quality.
- Data Cleaning and Transformation:
Standardized data types, corrected formatting issues, and resolved invalid or inconsistent values.
- Feature Engineering:
Created calculated fields, including binning continuous variables and converting Boolean values (TRUE/FALSE) into numeric format (0/1) using Excel formulas (e.g., IF statements) to support analysis.
- Data Analysis:
Built PivotTables to summarize key metrics and identify trends within the dataset.
- Data Visualization:
Developed charts and graphs to effectively communicate insights derived from the data.
- Dashboard Creation:
Designed an interactive Excel dashboard to present findings in a clear, user-friendly format.


## Insights:
- Advertising campaigns are successful. Users seeing ads are converting at a higher rate than PSA control users.
- Conversion rates increase with ad exposure, showing an increased likeliness that users will convert after repeated exposure, but levels plateau and drop off showing diminishing returns.
- User conversion behavior falls into expected times of day, some days showing higher conversions than others. Timing plays a role in campaign effectiveness.
## Final Conclusion:
The analysis shows that the advertising campaign is effective at increasing conversions in comparison to the PSA control group, with users exposed to ads at a higher rate. The results indicate that increased ad exposure generally leads to higher conversions, particularly at mid to lower exposure levels suggesting diminished returns at high exposure. Data shows conversions being higher in expected hours of the day and certain weekdays which could be useful for ad optimization. Overall, the data shows advertising positively impacts conversions, and campaign efficiency can improve by maximizing timing strategies.

