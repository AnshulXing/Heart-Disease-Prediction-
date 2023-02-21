# #Heart-Disease-Prediction

![heart](https://user-images.githubusercontent.com/86431802/203645458-bf9767b3-2e5a-4f2f-ae51-f80332fead5b.jpg)

<h2>>Introduction</h2>

World Health Organization has estimated 12 million deaths occur worldwide, every year due to Heart diseases. Half the deaths in the United States and other developed countries are due to cardio vascular diseases. The early prognosis of cardiovascular diseases can aid in making decisions on lifestyle changes in high risk patients and in turn reduce the complications. This research intends to pinpoint the most relevant/risk factors of heart disease as well as predict the overall risk using logistic regression.

![heart(2)](https://user-images.githubusercontent.com/86431802/203645689-9010ed5c-cd28-4f0d-ac91-0ccedf415464.jpg)















<h2>>Logistic Regression</h2>







<b>Logistic regression</b> is a type of regression analysis in statistics used for prediction of outcome of a categorical dependent variable from a set of predictor or independent variables. In logistic regression, the dependent variable is binary or dichotomous, i.e. it only contains data coded as 1 (TRUE, success, pregnant, etc.) or 0 (FALSE, failure, non-pregnant, etc.). Logistic regression is mainly used to for prediction and also calculating the probability of success.

<h3><i>                                                              logit(p)=b0+b1X1+b2X2+b3X3+...+bkXk                                                 </i></h3>



<h2>>Data Preparation</h2>

The dataset is publically available on the Kaggle website, and it is from an ongoing ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. The classification goal is to predict whether the patient has 10-year risk of future coronary heart disease (CHD).The dataset provides the patients’ information. It includes over 4,000 records and 15 attributes.





<h2>>Conclusions:</h2>




- **All attributes selected after the elimination process show Pvalues lower than 5% and thereby suggesting significant role in the Heart disease prediction.**

- **Men seem to be more susceptible to heart disease than women.Increase in Age,number of cigarettes smoked per day and systolic Blood Pressure also show increasing odds of having heart disease.**

- **Total cholesterol shows no significant change in the odds of CHD. This could be due to the presence of 'good cholesterol(HDL) in the total cholesterol reading.Glucose too causes a very negligible change in odds (0.2%)**

- **The model predicted with 0.92 accuracy. The model is more specific than sensitive.**

- **The Area under the ROC curve is 76 which is somewhat satisfactory.**

- **Overall model could be improved with more data.**




