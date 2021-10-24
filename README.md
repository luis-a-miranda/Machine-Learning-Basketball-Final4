# Machine Learning - 2016 College Basketball Final Four 
The goal of this project is to classify and predict which basketball teams are most likely to make it to the semifinals of a College Basketball Tournament.

Algorithms: KNN, Decision Tree, Support Vector Machine and Logistic Regression.

[Dataset URL](https://s3-api.us-geo.objectstorage.softlayer.net/cf-courses-data/CognitiveClass/ML0120ENv3/Dataset/ML0101EN_EDX_skill_up/cbb.csv)

## Conclusion

"In the case of totals betting in football and basketball, the breakeven point is 52.4 percent..." [[1]](#1). Therefore a 55% or above is considered very good as it indicates profits on conservative betting strategies.

Classification models accuracy are as following:

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
