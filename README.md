  # PM2.5 
   * Multiple linear regression
plt.figure(figsize=(12, 6))
sns.lineplot(data=data_cleaning[['pm25', 'pm25_predicted']])
plt.xlabel('Date')
plt.ylabel('PM2.5')
plt.title('Comparison between Actual PM2.5 and Predicted PM2.5')
plt.legend(['Actual PM2.5', 'Predicted PM2.5'])
plt.show()
  # Bank Customer Churn Prediction
  Supervised Learning
   * Logistic regression
   * Decision tree
   * SVM algorithm
   * Naive Bayes
