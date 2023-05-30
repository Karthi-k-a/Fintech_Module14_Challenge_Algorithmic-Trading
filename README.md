# Fintech Module 14 Challenge - Algorithmic Trading
![](https://github.com/Karthi-k-a/Fintech_Module14_Challenge_Algorithmic-Trading/blob/main/Images/14-challenge-image.png)

## Overview
A financial advisory firm constantly competes with the other major firms to manage and automatically trade assets in a highly dynamic environment. In recent years, it has heavily profited by using computer algorithms that can buy and sell faster than human traders. But, people still need to specifically program these systems, which limits their ability to adapt to new data. This project aims at improving the existing algorithmic trading systems and maintaining the firm’s competitive advantage in the market by enhancing the existing trading signals with machine learning algorithms that can adapt to new data.

The following steps were performed in [machine_learning_trading_bot](https://github.com/Karthi-k-a/Fintech_Module14_Challenge_Algorithmic-Trading/blob/main/machine_learning_trading_bot.ipynb) file to improve the existing algorithmic trading systems-
- Establish a Baseline Performance - Implement an algorithmic trading strategy that uses machine learning to automate the trade decisions.
- Tune the Baseline Trading Algorithm - Adjust the input parameters to optimise the trading algorithm.
- Evaluate a New Machine Learning Classifier- Train a new machine learning model and compare its performance to that of a baseline model.

## Results
**Establish a Baseline Performance**<br>
The provided SVM model generated an accuracy score of 55% with a high recall score (96%) for buying and a low recall score (4%) for selling. This indicates that the model performs extremely well in determining when to buy in trading.<br>
<br>
![](https://github.com/Karthi-k-a/Fintech_Module14_Challenge_Algorithmic-Trading/blob/main/Images/1.1.png)<br>
<br>
Cumulative return plot that shows the actual returns vs. the strategy returns-
![](https://github.com/Karthi-k-a/Fintech_Module14_Challenge_Algorithmic-Trading/blob/main/Images/1.png)

**Tune the Baseline Trading Algorithm**<br>
**Step 1:** Tune the training algorithm by adjusting the size of the training dataset (Increasied the training window to 6 months)<br>

<br>
![](https://github.com/Karthi-k-a/Fintech_Module14_Challenge_Algorithmic-Trading/blob/main/Images/tune.png)<br>
<br>
Cumulative return plot that shows the actual returns vs. the strategy returns-
![](https://github.com/Karthi-k-a/Fintech_Module14_Challenge_Algorithmic-Trading/blob/main/Images/tune1.png)


**Evaluate a New Machine Learning Classifier**
