
# TEMPERATURE PREDICTION USING MACHINE LEARNING MODELS 

## A Case Study of Construction Industries in Aberdeen, United Kingdom

The May 2018 dataset from Weather Research and Forecasting (WRF) a comprehensive world record of atmospheric datasets gives a high-resolution model of the earth's atmosphere, presenting weather as a fundamental element of life that impacts how we organise our hours, days, weeks, months, and years.

This study examines and analyses the Skin or Surface Temperature weather forecast for Aberdeen, located at Latitude 56.204 and Longitude 0.936, as it relates to the local infrastructure and building industries in Aberdeen. Dataset analysis and temperature prediction using Machine Learning Techniques are followed by a presentation of the model's accuracy and evaluation in predicting temperature values for the test dataset



## Author

- Aaron Joshua Loveday


## Business Problem

Environmental conditions, such as temperature, can have an impact on the performance and safety of buildings and other infrastructure in Aberdeen, United Kingdom. However, knowing how much effect temperature has on Aberdeen construction operations, as well as building models for predictions to project future extreme weather conditions has not been thoroughly explored.

This research aims to build a temperature prediction model that can be used for temperature prediction in Aberdeen Construction and Infrastructural Industries using Auto-Regressive Integrated Moving Average (ARIMA), Simple Linear Regression (SLR), Support Vector Regression (SVR), and Random Forest Machine Learning Techniques 
## Data

The May 2018 dataset from Weather Research and Forecasting (WRF) a comprehensive world record of atmospheric datasets was used in this study. This dataset gives a high-resolution model of the earth's atmosphere, presenting weather as a fundamental element of life that impacts how we organise our hours, days, weeks, months, and years.
## Methods

- This research was done using R and Excel Programming Software.

- The Parameter/variable used for analyses was Temperature

- 300 row was selected from the WRF dataset for cleaning and analyses

- Interpolation method was used to Handle nas with mean of neighbouring values.

- IQR was used for Outlier Detection and Mean imputation was used to handle Outliers.

- A time Step column was created for analysis alongside Temperature.

- Time Series Regression Analyses was carried out in the study.

- The parameter Temperature was splitted into training and testing set, 80% was used as training set and 20% was used to test the Models. 

- Machine Learning predictions were made using four Machine Learning Models namely, Autoregressive Integrated Moving Average (ARIMA),	Standard Linear Regression (SLR), Support Vector Regression (SVR), Random Forest (RF)

- The Main Hyper-parameters used were Standard for ARIMA and Linear Regression, Kernel for Support Vector Regression and N-Estimator for Random Forest

- Kernel type used were Polynomial, Linear and Radial Basis Function (RBF)

- N-Estimators 100, 200 and 500 trees were used for the Random Forest 

- The use of Root Mean Squared Error was used as the Main Evaluation Technique for the Machine Learning Algorithms. 

## Findings
The dataset used was WRF May 2018 dataset and the following was observed:

- Highest Temperature as recorded in Kelvin was observed between 28th and 31st May 2018.

- The best Performing Support Vector Regression hyper-parameter (Kernel) was Linear 

- The best Performing Random Forest hyper-parameter (N-Estimator) was N-Trees 200.

- N-Trees 200 was the best performing model as it is the model with the least root mean squared error



## Screenshots

### ARIMA Evaluation
Figure 1 - ARIMA RMSE
![ARIMA RMSE](https://github.com/Abimbojolo/JOSH_PORTFOLIO/assets/131364220/1b2c554c-fc05-4062-8c0c-f989da70a725)

### Linear Regression Evaluation
Figure 2 - SIMPLE LINEAR REGRESSION
![Simple Linear Reg RMSE](https://github.com/Abimbojolo/JOSH_PORTFOLIO/assets/131364220/8773fc1a-ad54-4ca5-bcf4-96002be1225c)


### Random Forest Evaluation and Comparison
Figure 3 - RANDOM FOREST (N-TREES 100)
![Random For 100](https://github.com/Abimbojolo/JOSH_PORTFOLIO/assets/131364220/95989412-4fd2-4c45-82fb-fa4171ef6f65)

Figure 4 - RANDOM FOREST (N-TREES 200)
![Random For 200](https://github.com/Abimbojolo/JOSH_PORTFOLIO/assets/131364220/2b291f54-8dc5-4840-ad31-907a728ef692)

Figure 5 - RANDOM FOREST (N-TREES 500)
![Random For 500](https://github.com/Abimbojolo/JOSH_PORTFOLIO/assets/131364220/6ecddf67-37e6-4fd7-a0b1-26d88332ea2b)


Figure 6 - BAR PLOT OF RANDOM FOREST MODEL
![Bar Plot of Random Forest Model](https://github.com/Abimbojolo/JOSH_PORTFOLIO/assets/131364220/827ecd4e-1568-4c03-8837-120c15b306e0)




### SVR Model Evaluation and Comparison
Figure 7 - SUPPORT VECTOR REGRESSION EVALUATION
![SVR Kernel Evaluation](https://github.com/Abimbojolo/JOSH_PORTFOLIO/assets/131364220/ec8577a2-7906-4491-986a-ce6617a230a0)

Figure 8 - SVR (LINEAR)
![SVR Linear](https://github.com/Abimbojolo/JOSH_PORTFOLIO/assets/131364220/a634b8c8-9abf-49e1-94e9-0d6b53ce53d5)

Figure 9 - SVR (POLY)
![SVR Poly](https://github.com/Abimbojolo/JOSH_PORTFOLIO/assets/131364220/6e5a62d2-00cb-4543-8fe4-a8e7c5d527bb)

Figure 10 - SVR (RADIAL)
![SVR Radial](https://github.com/Abimbojolo/JOSH_PORTFOLIO/assets/131364220/0e9d8a16-4bd0-4b94-b3bc-7939d4507718)



Figure 11 - BAR PLOT OF SVR MODEL PERFORMANCE
![Bar Plot of SVR Model Performance](https://github.com/Abimbojolo/JOSH_PORTFOLIO/assets/131364220/c14ad23f-f7e8-4d5a-bf74-d81f502a07af)






## Results

Figure 12 - ACTUAL AND PREDICTED PLOT OF 3 ML ALGORITHMS
![Actual and Predicted Values Correlation ](https://github.com/Abimbojolo/JOSH_PORTFOLIO/assets/131364220/fd60e7ee-1a00-4107-b24c-cb4698b3e201)




Figure 13 - EVALUATION OF BEST RMSE RESULTS IN ALL FOUR MODELS
![Evaluation best RMSE Results in all foour Models](https://github.com/Abimbojolo/JOSH_PORTFOLIO/assets/131364220/3264fd0c-c894-4029-bc4a-02ce01edfd80)

Figure 14 - BAR PLOT COMPARING BEST MODELS IN EACH ML ALGORITHM
![ANALYSIS OF ALL THE MODELS](https://github.com/Abimbojolo/JOSH_PORTFOLIO/assets/131364220/8b48d040-391d-4009-b5ac-98cea0211468)


The best performing model for Temperature Prediction in Aberdeen, United Kingdom is the Random Forest (200 Trees). This is as compared in Figure 14 Above






## Recommendations

Temperature is a major factor that influences the social and economic wellbeing of a city. it is therefore necessary to device a predictive model to understand future temperature conditions, so as to enhance proper planning.  
Based on Analysis and Predictive Models as conducted in the study, the use of Random Forest (200 trees) can be adopted in Temperature Prediction in Aberdeen United Kingdom. This will aid proper planning and help prevent socio-economic activity from the harshness of weather.
## Future Works

This study experimented with four different models: One (1) Condition Statistical Technique/Model (ARIMA) and Three (3) Modern Machine Learning Techniques/Model (Random Forest, SVR, and Linear Regression). Future works will be considered by finding out what the Modern or most recent Machine Learning and Modern Deep Learning Models are and how they can be applied to Weather Prediction. 