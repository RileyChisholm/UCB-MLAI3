# Project Summary
### Overview:
This project aimed to compare the performance of K Nearest Neighbor (KNN), Logistic Regression, Decision Trees, and Support Vector Machines (SVM) in predicting whether clients of a Portuguese bank would subscribe to a term deposit. The objective was to develop predictive models to enhance the bank's marketing strategies by accurately targeting potential customers.

### Dataset:
The dataset, sourced from the UCI Machine Learning repository, contains data from 17 marketing campaigns conducted between May 2008 and November 2010. It includes 41,188 entries and 21 features, covering client information, contact details, and social and economic context attributes. The target variable indicates if the client subscribed to the term deposit.

### Steps:
To prepare the data, categorical features were encoded using one-hot encoding, and the target variable was binarized ('yes' mapped to 1 and 'no' mapped to 0). The dataset was split into training and testing sets, with stratification to maintain the proportion of the target classes. A baseline accuracy of 88.73% was established, reflecting the proportion of clients who did not subscribe to the term deposit.

### Results:
Using the tuned models, the performance of each classifier was evaluated. Below is a summary of the results:

Before tuning the models:

![Screen Shot 2024-06-04 at 4 41 22 PM](https://github.com/RileyChisholm/UCB-MLAI3/assets/161158181/ab4d55a3-0a6e-4661-a9f9-0d4582410cf7)

After tuning the models:

![Screen Shot 2024-06-04 at 4 36 11 PM](https://github.com/RileyChisholm/UCB-MLAI3/assets/161158181/b8275e96-ab3d-44fb-8695-035d78f4109e)

### Visualizations

Confusion Matrix:

![Screen Shot 2024-06-04 at 4 38 28 PM](https://github.com/RileyChisholm/UCB-MLAI3/assets/161158181/92124c64-26d9-46fe-b61e-3c4d25fc36eb)

![Screen Shot 2024-06-04 at 4 38 48 PM](https://github.com/RileyChisholm/UCB-MLAI3/assets/161158181/e50531d6-72d0-4f17-ac15-d44740981666)

![Screen Shot 2024-06-04 at 4 39 03 PM](https://github.com/RileyChisholm/UCB-MLAI3/assets/161158181/44cf6a80-9e9e-4519-8950-a856c2e6653e)

![Screen Shot 2024-06-04 at 4 39 20 PM](https://github.com/RileyChisholm/UCB-MLAI3/assets/161158181/da4bf160-7628-4dec-9293-322297a6e7a8)


### Conclusion:
Despite achieving high accuracy, the models struggled with class imbalance, resulting in lower F1 scores. KNN and Decision Trees performed slightly better in identifying the minority class but still faced challenges. The results highlight the importance of addressing class imbalance in predictive modeling to improve model performance and reliability. Future work should explore advanced techniques to handle imbalance, such as SMOTE (Synthetic Minority Over-sampling Technique) or other resampling methods, to enhance the models' ability to predict the minority class effectively. This approach will lead to more accurate and actionable insights for targeted marketing strategies.
