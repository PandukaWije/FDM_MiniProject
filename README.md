# FDM_miniProject - Diabetes Risk Prediction Model
* Machine learning algorithms and statistical methods applied to this historical data to predict diabetes at an early stage.
* The dataset publicized by The Centers for Disease Control and Prevention (CDC), based in the United States. This dataset was found on Kaggle to predict which patients are at risk of diabetes using many features. 
* Class imbalance was detected in the pre-processing steps and we fixed the dataset using Synthetic Minority Oversampling Technique (SMOTE) 
> ![image](https://user-images.githubusercontent.com/88667109/206686033-ede1da24-4377-48fd-9cb0-450d479fd106.png)
> * Diabetes (Orange - 1) verses No Diabetes (Blue - 0)

* Using several alternative models, preprocessing techniques, and evaluation methods to select the most suitable model to make predictions.
* the classification models we used: 
> 1. Naïve Bayes 
> 2. K-Nearest
> 3. Logistic Regression models.

* After some evaluations (accuracy and f1 score) we have decided to go with the Naïve Bayes model 
> ![image](https://user-images.githubusercontent.com/88667109/206685647-e6b0367c-288b-49aa-b11c-afead366cd13.png)
> ![image](https://user-images.githubusercontent.com/88667109/206685671-af62962e-7d05-4872-a5c8-49326b724eb8.png)

* to host this application on the web we used the streamlit platform  
* this is the frontend that streamed by streamlet
> ![image](https://user-images.githubusercontent.com/88667109/206682905-9ad9a878-0cf7-4d07-aadf-54cb5871f14a.png)

