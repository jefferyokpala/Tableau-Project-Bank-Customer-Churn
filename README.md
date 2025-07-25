# Tableau Project-Bank Customer Churn

## Overview

Visualization of Bank Customer Churn dataset with Tableau

## Business Task

The objective of this data analysis project was to find customer behaviours that led to churn to predict future churn and mitigate it.

## Data Source

The dataset was obtained from Kaggle, and it can be found [here](https://www.kaggle.com/datasets/radheshyamkollipara/bank-customer-churn). It contains information about a bank's customers and their behaviors. It has 17 columns and 10,000 rows.

## Tools

Tableau

## Process

* I cleaned the dataset on MySQL Workbench, and the detailed explanation of the cleaning process can be found here.

* During the cleaning process on MySQL Workbench, I was able to understand what was in it and knew the parts of the data to visualize to help my analysis. I proceeded to load the dataset into Tableau and began working on it.

* On sheet 1 on Tableau, I created a pie chart to compare the number of customers who had exited (stopped doing business with) the bank and those who stayed. The visual showed that while a sizable majority keeps doing business with the bank, a large chunk of customers have exited. This is worth investigating further.

![image alt](https://github.com/jefferyokpala/Tableau-Project-Bank-Customer-Churn/blob/main/images/image8.png?raw=true)

* For further analysis, in Sheet 2, I created a vertical bar chart to show the average ages of the customers who exited and those who stayed. The findings made me realize that those who exited are on average seven years older than those who stayed on as customers. This suggests to me that the bank should put more effort into retaining its customers over the age of 40.

![image alt](https://github.com/jefferyokpala/Tableau-Project-Bank-Customer-Churn/blob/main/images/image1.png?raw=true)

* Next, in Sheet 3, I proceeded to find the correlation between satisfaction score and customer churn. The satisfaction score is rated on a scale of 1-5, and the average of those who exited is below 3. Meanwhile, the average of those who stay on as customers is slightly above three. The two numbers are not significantly far apart, but the trend is still worth keeping an eye on.

![image alt](https://github.com/jefferyokpala/Tableau-Project-Bank-Customer-Churn/blob/main/images/image7.png?raw=true)

* In Sheet 4, I looked for the correlation between credit score and the status of customers (exited vs. retained) and created a bar chart. While the average credit scores of the customers who exited are less than those of those who stayed, there is no statistical difference between them.

![image alt](https://github.com/jefferyokpala/Tableau-Project-Bank-Customer-Churn/blob/main/images/image3.png?raw=true)

* In sheet 5, I created a bar chart to visualize the average tenure of customers to see whether the amount of time a customer stayed with the bank has a correlation with their likelihood to remain a customer. The data shows that people who stay as customers for less than five years are more likely to exit than those who stay longer than five years.

![image alt](https://github.com/jefferyokpala/Tableau-Project-Bank-Customer-Churn/blob/main/images/image4.png?raw=true)

* Next, in Sheet 6,  I created a chart to find the correlation between customers who complained and those who exited. The data showed a near 1:1 correlation between those two categories. This strong correlation, coupled with analysis of the many other parts of the dataset, leads me to believe that customer complaints are the greatest indicator of their likelihood of churn.

![image alt](https://github.com/jefferyokpala/Tableau-Project-Bank-Customer-Churn/blob/main/images/image5.png?raw=true)

* In Sheet 7, I analyzed the correlation between the average balance of customers that exited vs. those that stayed on. Inexplicably, the customers who exited had a higher average bank balance than those who stayed. This seems counterintuitive to me, and I will discard this correlation from my analysis.

![image alt](https://github.com/jefferyokpala/Tableau-Project-Bank-Customer-Churn/blob/main/images/image6.png?raw=true)

* Lastly, I created a dashboard showing a summary of the relevant parts of the dataset for easy viewing and presentation.

![image alt](https://github.com/jefferyokpala/Tableau-Project-Bank-Customer-Churn/blob/main/images/image2.png?raw=true)
