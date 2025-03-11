# Credit-card-fraud-detection

 In this project, we focused on detecting fraudulent transactions in a highly
 imbalanced dataset. Since fraud cases are rare compared to legitimate ones, our
 main goal was to maximize recall to catch as many fraudulent cases as possible,
 even if it meant compromising on precision. We started by implementing baseline
 models like logistic regression, random forest, and decision trees to get an initial
 understanding of the performance we could expect. These models gave us a recall
 of around 80%, which was a good starting point but not quite at our target.
 To improve the results, we implemented an XGBoost classifier and adjusted
 the decision threshold, which helped us reach a recall of 90% while maintaining
 an acceptable precision of around 32%. Although this met our desired recall, we
 wanted to see if we could achieve even better performance. We then trained a
 deep neural network (DNN) with three hidden layers, using techniques like dropout
 and class weighting to handle data imbalance and prevent overfitting. The DNN
 surpassed our expectations.
 These findings show that while traditional machine learning models can provide
 decent results, a carefully designed DNN can significantly enhance fraud detection
 in imbalanced datasets. Future work could involve experimenting with ensemble
 methods or further tuning the models to see if we can improve the performance
 even more.
