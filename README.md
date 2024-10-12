# Coupon Acceptance Analysis Project

## Overview
Welcome to the Coupon Acceptance Analysis Project! This repository contains an exploration of customer behavior regarding coupon acceptance while driving. The study investigates various factors that influence whether a driver will accept a coupon for nearby restaurants, bars, or coffee houses.

## Project Goals
The primary goal of this project is to distinguish between customers who accepted a driving coupon versus those who did not. By analyzing data collected from a survey, we aim to uncover the dynamics of coupon acceptance in different driving scenarios.

## Data Description
The data for this project comes from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios, including the destination, current time, weather, passenger, etc., and asks participants whether they would accept a coupon if they were the driver. Responses are labeled as follows:
- **Y = 1**: Accepted the coupon (will drive there ‘right away’ or ‘later before the coupon expires’)
- **Y = 0**: Did not accept the coupon

### Attributes of the Dataset
The dataset includes the following user attributes:
- **Gender**: male, female
- **Age**: below 21, 21 to 25, 26 to 30, etc.
- **Marital Status**: single, married partner, unmarried partner, or widowed
- **Number of Children**: 0, 1, or more than 1
- **Education**: high school, bachelor's degree, associate's degree, or graduate degree
- **Occupation**: architecture & engineering, business & financial, etc.
- **Annual Income**: less than $12,500, $12,500 - $24,999, $25,000 - $37,499, etc.
- **Bar Visits**: 0, less than 1, 1 to 3, 4 to 8, or greater than 8
- **Takeaway Food Purchases**: 0, less than 1, 1 to 3, 4 to 8, or greater than 8
- **Coffee House Visits**: 0, less than 1, 1 to 3, 4 to 8, or greater than 8
- **Restaurant Visits (under $20)**: 0, less than 1, 1 to 3, 4 to 8, or greater than 8

## Analysis Methods
To analyze the differences between customers who accepted the coupon and those who did not, we will utilize:
- Statistical summaries
- Data visualizations using Python libraries
- Grouping and aggregating data to identify trends

## Insights
Preliminary findings suggest that factors such as frequency of bar visits, age, social dynamics, and income levels significantly influence coupon acceptance rates. For instance, drivers who frequent bars more than three times a month are more likely to accept bar coupons compared to those who visit less frequently.

## Getting Started
To explore the data and findings, clone this repository and run the Jupyter notebooks provided. Ensure you have the necessary Python libraries installed.

```bash
git clone https://github.com/yourusername/coupon-acceptance-analysis.git
cd coupon-acceptance-analysis
Contributions
Contributions are welcome! If you have suggestions for improvements or additional analyses, feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Special thanks to the UCI Machine Learning repository and Amazon Mechanical Turk for providing the data used in this analysis.
