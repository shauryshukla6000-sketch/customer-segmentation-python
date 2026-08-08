# Customer Segmentation & Marketing Analytics

## Overview
A Python-based business analytics project that segments customers using purchasing behavior, campaign response and digital engagement.

## Business objective
Identify meaningful customer groups and translate their characteristics into targeted marketing and retention strategies.

## Dataset
Marketing campaign/customer personality dataset containing 2,240 customer records and 29 source variables. The project uses the public dataset as an external data source.

## Workflow
1. Data audit and quality checks
2. Missing-value handling
3. Data-quality filtering
4. Feature engineering
5. Exploratory data analysis
6. Feature scaling
7. K-Means clustering
8. Elbow and silhouette analysis
9. PCA visualization
10. Segment profiling and business recommendations

## Python technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Engineered business features
- Age
- TotalSpend
- TotalPurchases
- CampaignAccepted
- HouseholdDependents
- WebEngagement

## Clustering approach
K-Means clustering is evaluated for k=2 through k=8. A 4-segment solution is selected as a practical business-oriented solution, balancing interpretability with cluster separation.

## Output
- `customer_segments.csv` — customer-level segment assignments
- `segment_profiles.csv` — segment-level summary
- `visualizations/` — elbow, silhouette and PCA charts

## Important
This project is an original implementation created for a portfolio. The public dataset and the referenced customer-segmentation concept were used as learning/reference material; the notebook, business framing, feature engineering and documentation were written specifically for this project.
