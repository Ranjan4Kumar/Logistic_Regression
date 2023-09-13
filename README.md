# Logistic_Regression
Dummy Example of Precision and Recall Threshold <br> 
** <br>

from sklearn.metrics import precision_recall_curve

precisions, recalls, thresholds = precision_recall_curve(y_true, y_predicted)

plt.plot(thresholds, precisions[:-1], "b--", label="Precision")

plt.plot(thresholds, recalls[:-1], "g-", label="Recall")
plt.show()
** <br>
