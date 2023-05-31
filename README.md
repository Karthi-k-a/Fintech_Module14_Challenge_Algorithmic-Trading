# Fintech Module 14 Challenge - Algorithmic Trading
![](https://github.com/Karthi-k-a/Fintech_Module14_Challenge_Algorithmic-Trading/blob/main/Images/14-challenge-image.png)

## Overview
A financial advisory firm constantly competes with the other major firms to manage and automatically trade assets in a highly dynamic environment. In recent years, it has heavily profited by using computer algorithms that can buy and sell faster than human traders. But, people still need to specifically program these systems, which limits their ability to adapt to new data. This project aims at improving the existing algorithmic trading systems and maintaining the firm’s competitive advantage in the market by enhancing the existing trading signals with machine learning algorithms that can adapt to new data.

The following steps were performed in [machine_learning_trading_bot](https://github.com/Karthi-k-a/Fintech_Module14_Challenge_Algorithmic-Trading/blob/main/machine_learning_trading_bot.ipynb) file to improve the existing algorithmic trading systems-
- Establish a Baseline Performance - Implement an algorithmic trading strategy that uses machine learning to automate the trade decisions.
- Tune the Baseline Trading Algorithm - Adjust the input parameters to optimise the trading algorithm.
- Evaluate a New Machine Learning Classifier- Train a new machine learning model and compare its performance to that of a baseline model.

## Results
### Establish a Baseline Performance
The provided SVM model generated an accuracy score of 55% with a high recall score (96%) for buying and a low recall score (4%) for selling. This indicates that the model performs extremely well in determining when to buy in trading.<br>
<br>
![](https://github.com/Karthi-k-a/Fintech_Module14_Challenge_Algorithmic-Trading/blob/main/Images/1.1.png)<br>
<br>
Cumulative return plot:<br>
![](https://github.com/Karthi-k-a/Fintech_Module14_Challenge_Algorithmic-Trading/blob/main/Images/1.png)

### Tune the Baseline Trading Algorithm
**Step 1: Tune the training algorithm by adjusting the size of the training dataset (Increased the training window to 6 months)**<br>
Accuracy score increased slightly from 55% (baseline model) to 56% and recall score for selling further decreased from 4% to 2%.<br>
<br>
![](https://github.com/Karthi-k-a/Fintech_Module14_Challenge_Algorithmic-Trading/blob/main/Images/tune.png) <br>
<br>
Cumulative return plot:<br>
![](https://github.com/Karthi-k-a/Fintech_Module14_Challenge_Algorithmic-Trading/blob/main/Images/tune1.png)

**Step 2: Tune the trading algorithm by adjusting the SMA input features (Increased short window to 8 and decreased long window to 20)**<br>
Accuracy score remained same as the baseline model (55%) and recall score for selling increased to 8%. This indicates that the tuned model will perform better in determining when to sell in trading.<br>
Strategy returns and Actual returns follow a similar pattern as compared to that of the baseline model, indicating the model's accurate prediction.<br>
<br>
![](https://github.com/Karthi-k-a/Fintech_Module14_Challenge_Algorithmic-Trading/blob/main/Images/tune2.png) <br>
<br>
Cumulative return plot:<br>
![](https://github.com/Karthi-k-a/Fintech_Module14_Challenge_Algorithmic-Trading/blob/main/Images/tune3.png)

### Evaluate a New Machine Learning Classifier
A new classifier (Logistic Regression Model) was used compare the performance of the orginal model. Accuracy score decreaed to 52%; however, the recall score for selling increased from 4% in the original model to 33% indicating the model would perform well in determining when to sell in trading.<br>
<br>
![](https://github.com/Karthi-k-a/Fintech_Module14_Challenge_Algorithmic-Trading/blob/main/Images/2.1.png)<br>
<br>
Cumulative return plot:<br>
![](https://github.com/Karthi-k-a/Fintech_Module14_Challenge_Algorithmic-Trading/blob/main/Images/2.png)
