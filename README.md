# Machine Learning - College Basketball (NCCA) Final Four 
The goal of this project is to classify and predict which basketball teams are most likely to make it to the semifinals of a College Basketball Tournament.

Algorithms: KNN, Decision Tree, Support Vector Machine and Logistic Regression.

[Dataset URL](https://s3-api.us-geo.objectstorage.softlayer.net/cf-courses-data/CognitiveClass/ML0120ENv3/Dataset/ML0101EN_EDX_skill_up/cbb.csv) obtained while enrolled on [Professional Certificate in IBM Data Science](https://www.edx.org/professional-certificate/ibm-data-science?index=product&queryID=f71f23095d28d770b5032557f7806f50&position=1).

## Results

"In the case of totals betting in football and basketball, the breakeven point is 52.4 percent..." [[1]](#1). Thus, above 57% can be consider as a good accuracy or being profitable, even with a conservative look, because 4.6% above break-even is acting as a buffer.

Concluding, profitability is expected if the models are used.

Lastly, classification models accuracy are as following:

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
