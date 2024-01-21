# Predictive-Modeling-for-Agriculture
Train a Logistic Regression model to pick the most important features that could help predict the crop accurately. Datacamp - Project: Predictive Modeling for Agriculture. Link: https://app.datacamp.com/learn/projects/1772

<p align="center">
<img src="https://github.com/mathewsrc/Predictive-Modeling-for-Agriculture/assets/94936606/d601863e-5b96-43b6-9d7e-70a57da43595" width=40% heigth=40%>
</p>

## Introduction

Measuring essential soil metrics such as nitrogen, phosphorous, potassium levels, and pH value is an important aspect of assessing soil condition. However, it can be an expensive and time-consuming process, which can cause farmers to prioritize which metrics to measure based on their budget constraints.

Farmers have various options when it comes to deciding which crop to plant each season. Their primary objective is to maximize the yield of their crops, taking into account different factors. One crucial factor that affects crop growth is the condition of the soil in the field, which can be assessed by measuring basic elements such as nitrogen and potassium levels. Each crop has an ideal soil condition that ensures optimal growth and maximum yield.

## Dataset description
```
"N": Nitrogen content ratio in the soil
"P": Phosphorous content ratio in the soil
"K": Potassium content ratio in the soil
"pH" value of the soil
"crop": categorical values that contain various crops (target variable).
Each row in this dataset represents various measures of the soil in a particular field. Based on these measurements, the crop specified in the "crop" column is the optimal choice for that field.
```

## Objective

This project applies machine learning to build a multi-class classification model to predict the type of "crop" while using techniques to avoid multicollinearity, which is a concept where two or more features are highly correlated.

## Step by step diagram

![image](https://github.com/mathewsrc/Predictive-Modeling-for-Agriculture/assets/94936606/3b38b459-cf9f-4ec7-a788-6b53016e50aa)

