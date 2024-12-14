![image](https://github.com/user-attachments/assets/f2c917c1-56db-4d17-950a-3f8d119eb23d)
# FleetCor: Cross-Sell Strategy Enhancement and Model Building

## Executive Summary
This project aims to refine Corpay's Cross-Sell Program by leveraging data analytics and predictive modeling to optimize customer selection and boost profitability. By analyzing customer performance data and implementing Logistic Regression, Decision Tree, and Random Forest models, we identified high-creditworthiness profiles and key performance metrics.

## Key Business Outcomes
- **Optimized Eligibility Model:** Enhanced criteria based on Days Past Due (DPD), NSF occurrences, and account activity.
- **Targeted Opportunities:** Identified 13 customers for exclusion and 601 for inclusion in the Universal Card program.
- **Revenue Uplift:** Projected a 15.60% increase in revenue.
- **Comprehensive Analysis:** Delivered insights via a Power BI dashboard showcasing delinquency, write-offs, spend, and revenue by various dimensions.

## Data Preparation
- **SQL Queries:** Structured unstructured data into views, aggregated by transaction details.
- **Alteryx:** Improved data quality by addressing missing values.
- **Feature Engineering in R:** Transformed variables, normalized data, and mitigated multicollinearity using VIF.

## Predictive Models
### Logistic Regression
- **Accuracy:** Training: 89.20%, Validation: 89.70%.
- **Outcome:** Risk categorization into "Risky" or "Not Risky" based on NSF payments.

### Decision Tree
- **Complexity Control:** Pruned tree (cp=0.007).
- **Insights:** Visual decision-making paths using rpart.

### Random Forest
- **Performance:** Accuracy improved with 500 trees and variable importance analysis.
- **Visualization:** Feature importance plotted for actionable insights.

## Recommendations
1. **Maintain Data Quality:** Regular updates and cleaning to ensure model robustness.
2. **Expand Variables:** Explore additional features for deeper insights.
3. **Periodic Model Updates:** Integrate new data for continuous improvement.

## Conclusion
Corpay's adoption of advanced analytics positions it as a leader in leveraging data science for strategic decisions. The models developed not only optimize profitability but also enhance risk management, paving the way for sustained competitive advantage.

---

### Repository Structure
- **`Data_For_Modelling.csv`:** Cleaned and preprocessed dataset.
- **`scripts/`:** R scripts for Logistic Regression, Decision Tree, and Random Forest models.
- **`results/`:** Key findings and prediction outputs.

### Contact
For inquiries, please reach out at [eshambr@outlook.com].
