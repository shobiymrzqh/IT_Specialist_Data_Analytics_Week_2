# Data_Analytic_Week_2
## Types of Data analysis
### 1) Descriptive analysis
Descriptive analysis is a form of data examination that assists in the portrayal, illustration, or informative consolidation of data points, enabling the emergence of patterns that fulfill all the criteria of the dataset.

### 2) Diagnostic analysis
Diagnostic analytics examines data to understand the root causes of events, behaviors, and outcomes. Data analysts use diverse techniques and tools to identify patterns, trends, and connections to explain why happened.

### 3) Predictive analysis
Predictive analytics seeks to anticipate future events by examining historical data, employing statistical modeling, machine learning, and artificial intelligence to project potential outcomes.

### 4) Prescriptive analysis
Prescriptive analytics delves beyond predictive analytics, examining the correlation between specific variables and their influence on the ultimate result. Its emphasis lies in determining the actions necessary to achieve desired outcomes.
### Example: 
#### Study case
title: Lack of public interest in using online driver than traditional driver

In Jakarta City, traditional driver (ojek pangkalan) has long been a favorite transportation option for locals. However, in recent years, there has been a significant decline in interest in using traditional driver. traditional driver have reported a significant drop in income, while users have also turned to other alternatives such as online online online driver and public transportation. 

- Root causes
    - Technology Imbalance
    - Lack of Innovation
    - Consumer Awareness

- Solution
    - Technology Imbalance
        - Collaborate with online driver applications for integration with online driver services, so that users can choose between online driver and traditional driver in one application. 
        - traditional driver can develop their own applications or digital platforms to improve service quality, price transparency, and convenience for consumers.
    - Lack of Innovation
        - Conduct training for traditional driver to blend with technology
        - Conduct training to traditional driver to improve service quality. Good service quality is an attraction for consumers
    - Consumer Awareness
        - Partnerships with local communities such as community organizations or youth groups, to disseminate information about services at traditional driver.
        - Free demonstration and trial programs where the public can try services at traditional driver bases for free or with discounts

## Data Storytelling
Data storytelling is a method used to convey information by combining data, visualization, and narrative in one unit.

### Why Use Data Storytelling?
#### - Presenting data in a more interesting and understandable way.
By presenting data in the form of a narrative/story, stakeholders can more quickly and easily understand the information presented.

#### - Helps communication
With data storytelling, data analysts can ensure that everyone, regardless of their background and technical knowledge, can understand the data well

#### - Improving decision-making
By understanding the story behind the data, decision makers (such as executives or managers) can make more informed decisions based on facts

#### -Attract attention and engagement
Using data storytelling, analysts can increase the engagement and participation of non-technical stakeholders in data-driven discussions and decision-making.

#### Example
dataset: 

![Screenshot (864)](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_2/assets/134476980/f111d3d8-59cd-4ee7-aa5d-327003f6e309)

uses df.describe() to display data such as mean, median, mode, max, min.

![Screenshot (862)](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_2/assets/134476980/d0c3f75c-4272-4446-a129-03762eba28cf)

COVID-19 is an infectious disease caused by a newly discovered strain of coronavirus. This new virus and the disease it causes were unknown before the start of the outbreak in Wuhan, China, in December 2019. COVID-19 has become a pandemic in many countries around the world. In the analysis of COVID-19 data from several selected countries, there are approximately 50 million total covid cases in the world. The average total deaths were 31 thousand, where the lowest number of deaths was 21 out of a total of 62 thousand cases in Bhutan. On the other hand, India stands out with the highest number of deaths, reaching a total of 532 thousand deaths from . Although India has the largest population among the selected countries, the high testing effort with 930 million tests shows commitment in handling the pandemic. However, the complexity of handling the pandemic in India is compounded by the large scale of the population. This highlights the importance of an adaptive and effective coping strategy in the face of the COVID-19 pandemic.
    India's high testing and population suggest continued COVID-19 challenges. Without effective containment and vaccination, cases and deaths may rise. Other countries with successful vaccination efforts may see declines, but new variants could alter outcomes globally.

## Correlation
Correlation analysis is a statistical technique used to measure the strength and direction of the linear relationship between two quantitative variables. In Jupyter Notebook, you can effectively perform correlation analysis using Python libraries like pandas and seaborn.

### Correlation Positive (+) and Negative (-)
- Positive correlation (+): When one variable increases, the other tends to increase as well. A correlation coefficient closer to +1 signifies a stronger positive relationship.
- Negative correlation (-): When one variable increases, the other tends to decrease. A correlation coefficient closer to -1 indicates a stronger negative relationship.

Example:![correlation](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_2/assets/101807673/7dc2638e-0c29-4e79-9558-7667f1c0e90d)


## T-Tests
T-tests are a family of statistical procedures used to compare the means of two groups. They are a fundamental tool in inferential statistics, allowing to assess whether the observed difference between two groups is likely due to random chance or reflects a true underlying difference in the population.

There are different types of t-tests depending on the characteristics of your data and the research question:
### 1.	Independent Samples T-test: 
Used to compare the means of two independent groups.

![image](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_2/assets/165742717/8620d7d2-d494-4280-ac3a-06e887421bf2)


### 2.	Paired Samples T-test: 
Used to compare the means of two groups where the same subjects are involved.

![image](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_2/assets/165742717/90d4c591-e978-4ab3-9b57-703054476d57)


### 3.	One-Sample T-test: 
Used to compare the mean of a single sample to a hypothesized value.

![image](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_2/assets/165742717/5410f66d-0bc1-4802-be46-7ad466fca897)


##### Example (Paired Sample T-Test) :

![image](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_2/assets/165742717/26834e25-c6da-46e0-9281-222370b7deb4)



## Machine Learning Regression
Regression is a statistical method used to understand and model the relationship between one or more independent variables and a dependent variable. The main purpose of regression analysis is to understand the extent to which the independent variables contribute to the variation in the dependent variable, as well as to predict the value of the dependent variable based on the values of the independent variables.
- There must be historical data
- The historical data must be patterned
- Complex algorithm

### 1) Preprocessing Model
An important stage in the development of a good model. It involves a series of steps to clean, transform and prepare the data to make it suitable for use in regression models.
![image](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_2/assets/165861920/ed81d80c-df45-4ebe-907d-2a26f12bbff8)

### 2) Machine Learning Regression - Simple Linear Regression
#### a) Splitting Training and Test Set
This allows us to evaluate the model's performance on never-before-seen data, which helps ensure that the model not only learns the patterns in the training data but is also able to generalize well to new data.
![image](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_2/assets/165861920/873a6b67-e6f2-47f0-8cf5-826bf0dc6c6b)

#### b) Filling Into Training
The process of filling in (imputing) missing values in the training dataset before training the regression model. This is important because most machine learning algorithms cannot handle missing values, so special handling of incomplete data is necessary.
![image](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_2/assets/165861920/c0a27bcb-8ed0-4d2f-a5f0-1d86b8e671ef)

#### c) Predict The Result
The process of using a trained regression model to make predictions or estimates of the value of the dependent variable (response) based on the given values of the independent variables (predictors).
![image](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_2/assets/165861920/f11e0d32-f582-4ad1-9ffa-2cdf39c0c10f)

#### d) Plot The Result
The process of visualizing the predicted results produced by a regression model against the actual observed data is often useful for visualizing how well our model fits the actual data.
- Tabel
![image](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_2/assets/165861920/fbdf5778-6e88-4063-97fd-b1cfa427e35b)
- Bar
![image](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_2/assets/165861920/123b57f1-9ace-4815-864e-307cf200a8f2)
- Scatter Plot
![image](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_2/assets/165861920/b86522ff-a836-41fe-9e8a-154aaae899e9)

### 3) Evaluate Model
Model evaluation in regression serves to measure how well the trained model maps the relationship between the independent and dependent variables in the data. This evaluation helps us understand how accurate the model is in making predictions for data that has never been seen before.

- Mean Squared Error (MSE):

Measures the average of the squared differences between the true value of the dependent variable and the value predicted by the model. The lower the MSE value, the better the model is at making predictions.
![image](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_2/assets/165861920/9cf57bf8-0d67-400a-b580-7fae30cc33cd)

- Mean Absolute Error (MAE):

The average of the absolute values of the difference between the true value of the dependent variable and the value predicted by the model. MAE gives an idea of how close the model prediction is to the true value, regardless of the direction of the difference.
![image](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_2/assets/165861920/dc14ccd0-d24f-4742-86ff-2fb514b91e66)

- Mean Absolute Percentage Error (MAPE):

A commonly used evaluation metric in regression to measure the relative accuracy of the model in making predictions as a percentage of the true value. 
![image](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_2/assets/165861920/e96bdfb1-c96f-4452-b9ea-32d546d595d6)

- Coefficient of Determination (𝑅2):

Measures how well the variability in the dependent variable can be explained by the model. The value of 𝑅2 ranges from 0 to 1, where a higher value indicates a better model in explaining the variation in the data.
![image](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_2/assets/165861920/fdba0b49-e7c4-4027-a34d-016133c9ae65)

### Artificial Intellegence (AI) VS Machine Learning (ML) VS Deep Learning (DL)
In the context of AI, Machine Learning is one of the approaches used to achieve AI goals, while Deep Learning is a technique used in Machine Learning to model highly complex data using deep artificial neural networks. All of this is part of an effort to create intelligent systems that are able to learn from data in a human-like manner.





