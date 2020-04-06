<p align="center">
  <h2 align="center">Churn-Prediction
  <h3 align="center">How to predict which customers are likely to churn and take steps to reduce churn rate</h3>
  </h2>
</p>

<b>Retention Rate</b> is one of the most critical metrics. It is an indication of how good is your product market fit (PMF). If your PMF is not satisfactory, you should see your customers churning very soon. One of the powerful tools to improve Retention Rate (hence the PMF) is Churn Prediction. This will make you understand which customers are likely to stay on the system and who are likely to leave, so that you can take necessary steps to retain the customers likely to churn.

Make clusters based on few numerical variables likely to lead to churn. We add these cluster values to the original dataset. After all the data preparation, we apply machine learning algorithm on the dataset which also contains cluster values based on certain parameters now. The machine learning algorithm accuracy is checked. We have used XGBoost feature importance to understand the most important features and then apply ML algos only on the most important features. Now we recheck the accuracy of the ML Algorithm.
