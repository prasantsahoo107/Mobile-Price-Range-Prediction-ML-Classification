# Mobile-Price-Range-Prediction-ML-Classification
In this project, we are going to explore and analyze a dataset which contains specifications of two thousand mobile phones and try to predict optimum price ranges for a list of mobile phones in the market by applying various machine learning algorithms such as logistic regression, decision tree, random forest and xgboost

## Data Set Features
```

Battery_power - Total energy a battery can store in one time measured in mAh
Blue - Has bluetooth or not
Clock_speed - speed at which microprocessor executes instructions
Dual_sim - Has dual sim support or not
Fc - Front Camera mega pixels
Four_g - Has 4G or not
Int_memory - Internal Memory in Gigabytes
M_dep - Mobile Depth in cm
Mobile_wt - Weight of mobile phone
N_cores - Number of cores of processor
Pc - Primary Camera mega pixels
Px_height - Pixel Resolution Height
Px_width - Pixel Resolution Width
Ram - Random Access Memory in Mega
Touch_screen - Has touch screen or not
Wifi - Has wifi or not
Sc_h - Screen Height of mobile in cm
Sc_w - Screen Width of mobile in cm
Talk_time - longest time that a single battery charge will last when you are
Three_g - Has 3G or not
Wifi - Has wifi or not
Price_range - This is the target variable with value of 0(low cost), 1(medium cost), 2(high cost) and 3(very high cost).

```
## Problem Statement
The problem at hand is to determine the optimal price range for a list of mobile phones in the market by utilizing a dataset containing specifications of two thousand mobile phones. The objective is to identify the key features that significantly affect the pricing of mobile phones and apply various machine learning algorithms, including logistic regression, decision tree, random forest, and k-nearest neighbors (knn), to predict the ideal price range for the given list of phones.

The primary challenge is to analyze the vast dataset and identify the most relevant features that influence the pricing of mobile phones accurately. Additionally, selecting the most appropriate machine learning algorithm that can deliver accurate predictions is another challenge that needs to be addressed.

By solving this problem, we can help companies make informed decisions on pricing and feature prioritization, which can lead to higher sales and profits. The findings of this project can also help companies develop more competitive products and gain an edge over their rivals in the highly competitive mobile phone market.



## ML Algorithims Used
1. Logistic Regression
2. Random Forest
3. Decision Tree
4. XGBoost

## Conclusions
```
Mobile phones are available in 4 different price ranges with a roughly equal number of devices in each range.
Half of the phones have Bluetooth capability, while the other half do not.
As the price range increases, there is a gradual increase in battery life.
RAM performance shows a continuous increase as the price range moves from low cost to very high cost.
More expensive phones tend to be lighter in weight.
The significant factors affecting the price range of mobile phones include RAM, battery power, and pixel quality.
Both logistic regression and XGboosting yielded the best results when using hyperparameters.
```
