# An-Analytical-Study-on-Predicting-Customer-Churn-in-the-Telecommunications-Sector-Machine-Learning
The goal of this study is to use machine learning approaches to anticipate customer attrition inside an Iranian telecoms business. This study used data from the UCI Machine Learning Repository [1], with Logistic Regression and Random Forest as the key machine-learning classification techniques
# I.	INTRODUCTION 
Customer churn prediction refers to the analytical process aimed at identifying customers who are likely to discontinue their patronage or switch from their current service provider due to various factors [2]. The fundamental goal of churn prediction models is to identify customers who are likely to leave, allowing for the focused implementation of retention efforts. This approach helps businesses thrive by increasing total income through effective client retention [3].
# II.	DATA DESCRIPTION
This study's dataset, which included 3150 customer records, was obtained from the UCI Machine Learning Repository [1]. It includes a variety of factors like as client demographics, service consumption habits, and account information. 
# III.	METHODOLOGY
--------------
This study takes a dual strategy, using exploratory data analysis (EDA) to uncover business intelligence insights for data-driven decision-making, and predictive analysis using two machine learning algorithms to anticipate customer attrition. The first phases entailed thorough data cleansing, during which it was discovered that the dataset was missing no values. However, a transformation was required to translate numerical values into categorical variables, allowing for deeper insights and more informed decision-making.
After completing the exploratory data analysis (EDA), the study moved on to the predictive modelling phase. At this step, two machine learning classification techniques were used: Logistic Regression and the Random Forest Classifier. The Logistic Regression technique, highly renowned for its application in binary classification issues, is preferred for its simplicity and interpretability, making it an excellent choice for preliminary investigations [5]. The Random Forest algorithm, a method in the ensemble learning category, on the other hand, is known for its excellent accuracy and competency in handling huge datasets with high dimensionality [6]. Various performance indicators, including as accuracy, precision, and the F1 score, were used to assess the usefulness of these algorithms. This evaluation sought to identify the best performing algorithm in the circumstances of the research.

IV.	RESULT
--------------
The Exploratory Data Analysis (EDA) revealed numerous critical findings, including a 16% turnover rate. Although this figure appears to be low, it nevertheless represents a possible loss of key clients to competitors. According to the age distribution research, the bulk of clients are in the core middle age category, followed by the medium age group. The older and younger age groups, which have lesser network activity, are at the bottom of this distribution.

Finally, the EDA examined the impact of customer complaints on turnover rates. consumers who did not file complaints had a relatively low turnover rate, but a significant number of consumers who filed complaints were more likely to quit. This conclusion is consistent with the expectation that disgruntled consumers will cease service.
The original dataset, which was already in integer format, was used for the predictive modelling part of the study. Because the data required no further feature engineering, the recommended machine learning techniques could be used directly.
The findings below exhibit the performance details of two machine learning models, Logistic Regression and Random Forest, used to forecast customer attrition in a telecom scenario. Let's compare the two models based on each metric:
TABLE I. 	MODEL EVALUATION
Model	Accuracy	Precision	Recall	F1 Score	ROC AUC Score
LR	0.85	0.42	0.15	0.22	.056
RF	0.95	0.81	0.82	0.81	0.893

VI.	CONCLUSION
--------------

The research effectively illustrates the application of machine learning algorithms in forecasting customer turnover in the telecoms industry. The Random Forest model, in particular, produced encouraging outcomes in the setting of the Iranian telecom sector. These data can help telecommunications businesses improve their client retention tactics. To generalise these findings further, future study might look at different machine learning approaches or more varied datasets.
In summary, the Random Forest model beats the Logistic Regression model for this particular problem across all measures. It is more accurate, dependable, and effective in differentiating between positive (churn) and negative (non-churn) classes.3

V.	DISCUSSION
--------------

The Random Forest model's improved performance can be ascribed to its ability to manage the dataset's complicated, non-linear connections. These findings are especially important for telecom firms in Iran, who face significant customer turnover rates. The extent of the dataset and the inherent biases of the chosen algorithms, however, limit the scope of the study.

# REFERENCES
[1]	"Churn Dataset." UCI Machine Learning Repository. Accessed 2023. [Online]. Available: https://archive.ics.uci.edu/datasets?search=churn
[2]	Coussement, K., & Van den Poel, D. (2008). Buckinx, W., & Van den Poel, D. (2005).
[3]	Hashmi, N., Butt, N. A., & Iqbal, M. (Year). "Customer Churn Prediction in Telecommunication: A Decade Review and Classification." Department of Computer Science and Information Technology, Faculty of Computer Science and Information Technology, University of Gujrat, Pakistan.
[4]	Mahajan, V., Misra, R., & Mahajan, R. (2015). "Review of Data Mining Techniques for Churn Prediction in Telecom." Journal of Information and Organizational Sciences, vol. 37, no. 2
[5]	Hosmer Jr, D. W., Lemeshow, S., & Sturdivant, R. X. (2013). Applied Logistic Regression. John Wiley & Sons.
[6]	Breiman, L. (2001). Random Forests. Machine Learning, 45(1), 5-32.
