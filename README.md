# Credit-card-fraud-detection

Fraud detection is a crucial task in many fields, especially when dealing with highly
imbalanced datasets where fraudulent cases are rare compared to legitimate ones. The
main goal of this project is to detect as many fraudulent cases as possible while keeping
the number of false positives at an acceptable level. To achieve this, we started with
simple baseline models to establish a reference point and then moved on to more advanced
techniques. The focus was on maximizing recall, as missing fraudulent cases is a bigger
problem than falsely flagging legitimate ones. We implemented and compared several
machine learning models, including logistic regression, random forest, XGBoost, and
deep neural networks (DNNs), and applied various optimization techniques to improve
their performance. This allowed us to identify which model works best for handling the
challenges of fraud detection in an imbalanced dataset.

The dataset "Credit Card Fraud Detection Predictive Models" contains collected data
from European transactions made in September 2013. The data were retrieved over the
span of two days, where each instance was being labeled as either fraudulent or non-fraud.
Of the 284 807 instances, only 492 are labeled as fraudulent, which is only 0. 172%. This
makes the data set highly unbalanced.
Each instance contains 30 features, of which all are numerical. Due to confidentiality,
28 out of the 30 features were transformed by using PCA. The only features
that contain information about what they represent are the "time of transaction" and
"amount of money per transaction". In case of fraud, the data instances are labeled 1 and
0 otherwise. Data preprocessing will mainly focus on balancing the dataset, since other
preprocessing factors have already been accounted for, such as missing data points.

This project was made during my international semester in Seoul National University of Science and Technology in South Korea. The whole project was made by a group of four students. The jupyter notebook was only edited and commented by me but the report was done with the contribution of everyone. This was my first project in Machine learning and deep learning that's why there is a lot of room for improvement. However, the results are very convincing and I will improve this project as I gain knowledge and practice in the field.   
