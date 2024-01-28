# Sampling Assignment

In this python code, we have used sampling techniques on a credit card fraud detection dataset 
and then applied various ML models on the dataset to find out which Model,sampling technique combination
gives us the best accuracy.


Following 5 sampling Techniques were used:

1. Random Under Sampler (Sampling1)
2. Random Over Sampler (Sampling2)
3. SMOTE (Sampling3)
4. Near Miss (Sampling4)
5. Stratified KFold(Sampling5)


The Sample size was calculates using the following formula: n = Z^2(p(1 – p)/m^2) where: 
n = sample size
Z = z-value (for 99% confidence interval, Z = 2.576)
p = proportion of the minority class (taken as 0.5 for a balanced dataset)
m = margin of error (taken as 0.05 for a sample size of 1000)


Following 5 models were applied on the sampled dataset:
1. Logistic Regression (M1)
2. Decision Tree Classifier (M2)
3. Random Forest Classifier (M3)
4. Support Vector Classifier (SVC) (M4)
5. KNN Classifier (M5)


On execution of the code, following results were obtained:
The cells of the table represent accuracy of the applied model using the respective sampling technique.

![](https://github.com/maheshmani13/Sampling/blob/main/Results.png)

