# BE-BH-Practical-Application-Assignment-5.1 - Analysis of Bar Coupon Acceptance

Overview

This project aims to analyze the factors influencing the acceptance of bar coupons among drivers. The dataset used for this analysis is sourced from the UCI Machine Learning Repository and contains various attributes related to user demographics, behavior, and contextual factors. The primary goal is to identify patterns and trends that explain the likelihood of a driver accepting a bar coupon.

File Description

prompt_5_1_Assignment_Chandra_Vempati.ipynb: This Jupyter notebook contains the detailed analysis and visualizations used to investigate the acceptance rates of bar coupons among different driver groups.

Dataset

The dataset includes the following attributes:

User attributes: Gender, Age, Marital Status, Number of children, Education, Occupation, Annual income, etc.
Behavioral attributes: Number of times a user goes to a bar, buys takeaway food, goes to a coffee house, eats at a restaurant with an average expense less than $20 per person.
Contextual attributes: Driving destination, Location of user, coupon and destination, Weather, Temperature, Time, Passenger.
Coupon attributes: Time before it expires.
Target attribute: Whether the customer accepts the coupon or not.

Key Analysis and Findings

Frequency of Bar Visits: Drivers who visit bars more than once a month are more likely to accept bar coupons.
Passenger Influence: Drivers who do not have children as passengers are more likely to accept bar coupons.
Marital Status: Drivers who are not widowed are more likely to accept bar coupons.
Age Factor: Drivers under the age of 30 are more likely to accept bar coupons.
Restaurant Visits and Income: Drivers who visit cheap restaurants more than four times a month and have an income of less than $50K are more likely to accept bar coupons.

Hypotheses

Based on the observations, the following hypotheses can be made about drivers who accepted the bar coupons:

Younger drivers, frequent bar-goers, and those without children as passengers are more likely to accept bar coupons.
Individuals who frequently dine out at budget-friendly establishments and have moderate incomes might be more attracted to additional savings through coupons.

Instructions

To run the analysis on your local machine:

1) Clone this repository.
2) Ensure you have the necessary libraries installed. You can install the required libraries using:

Copy code

pip install pandas matplotlib seaborn scikit-learn

Open the Jupyter notebook prompt_5_1_Assignment_Chandra_Vempati.ipynb and run the cells to see the analysis and visualizations.

Conclusion

This project provides insights into the factors affecting the acceptance of bar coupons among drivers. The findings can be used to tailor marketing strategies and promotional offers to target specific segments more effectively.

Acknowledgements
The dataset is sourced from the UCI Machine Learning Repository.
This analysis was conducted as part of an assignment by Chandra Vempati.

