# Machine Learning - College Basketball (NCCA) Final Four 
Analyze and predict the teams that are likely to reach the semifinals of the College Basketball Tournament (NCAA) using machine learning algorithms.

## Key Features
1. Algorithm Selection: The project utilizes K-Nearest Neighbors (KNN), Decision Tree, Support Vector Machine (SVM), and Logistic Regression algorithms.
2. Accuracy Evaluation: The classification models' accuracy, F1-score, Jaccard index, and LogLoss are evaluated to determine their effectiveness in predicting the Final Four teams.

Dataset: [NCCA_db](https://s3-api.us-geo.objectstorage.softlayer.net/cf-courses-data/CognitiveClass/ML0120ENv3/Dataset/ML0101EN_EDX_skill_up/cbb.csv).

## Results

"In the case of totals betting in football and basketball, the breakeven point is 52.4 percent..." [[1]](#1). Thus, above 57% can be consider as a good accuracy or being profitable, even with a conservative look, because 4.6% above break-even is acting as a buffer.

Based on the results, utilizing the classification models is expected to provide profitable insights for predicting the Final Four teams in the College Basketball Tournament.

The classification models' accuracy scores are as follows:

| Algorithm           | Accuracy | F1-score | Jaccard  | LogLoss |
| ------------------  | -------- | -------- | -------- | ------- |
| KNN                 | 0.628571 | 0.628571 | 0.458333 | NA      |
| Decision Tree       | 0.657143 | 0.657143 | 0.489362 | NA      |
| SVM                 | 0.571429 | 0.571429 | 0.400000 | NA      |
| Logistic Regression | 0.685714 | 0.685714 | 0.521739 | 1.03719 |

## References
<a id="1">[1]</a> 
Paul, R. J., and Weinbach, A. P. (2005). 
Bettor misperceptions in the NBA: The overbetting of large favorites and the “hot hand”. 
*Journal of Sports Economics*, 6(4), 390-400. 
