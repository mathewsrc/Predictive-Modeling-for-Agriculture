# Predictive-Modeling-for-Agriculture
Train a Logistic Regression model to pick the most important features that could help predict the crop accurately

<p align="center">
<img src="https://github.com/mathewsrc/Predictive-Modeling-for-Agriculture/assets/94936606/305882e5-78ca-4aed-ae67-41c1bb18750c" width=40% heigth=40%>
</p>

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

This project applies machine learning to build a multi-class classification model to predict the type of "crop" while using techniques to avoid multicollinearity, which is a concept where two or more features are highly correlated.
