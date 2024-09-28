# Ukraine vs Russia Conflict: Aid and Death Toll Analysis

## Overview
This project analyzes the humanitarian crisis resulting from the Ukraine conflict, focusing on understanding the types of aid provided and predicting the death toll from the conflict. Our goal is to support those affected by the war by providing insights into the aid distribution and its impact.

## Table of Contents
- [Business Problem](#business-problem)
- [Background and History](#background-and-history)
- [Data Sources](#data-sources)
- [Data Explanation](#data-explanation)
- [Data Cleaning and Transformation](#data-cleaning-and-transformation)
- [Modeling and Evaluation](#modeling-and-evaluation)
- [Findings and Analysis](#findings-and-analysis)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [License](#license)

## Business Problem
The war in Ukraine has led to a significant humanitarian crisis. It is challenging to track the amount of aid being provided and its impact. The goal of this project is to analyze the types of aid sent and predict the associated death toll.

## Background and History
Since the conflict began, the international community has mobilized to provide aid. Understanding the flow of resources and the human cost of the war is crucial for effective responses.

## Data Sources
The sources of the datasets are Kaggle and the Institute For The World Economy. We downloaded the data and saved them into this github repo.
- [Ukraine Support Tracker](https://raw.githubusercontent.com/kueyram/Analysis-of-Ukraine-vs-Russia-conflict/main/data/Ukraine_Support_Tracker_Release_18.xlsx)
- [Personnel Losses Dataset](https://raw.githubusercontent.com/kueyram/Analysis-of-Ukraine-vs-Russia-conflict/refs/heads/main/data/personnel_losses.csv)
- [Equipment Losses Dataset](https://raw.githubusercontent.com/kueyram/Analysis-of-Ukraine-vs-Russia-conflict/refs/heads/main/data/equipment_losses.csv)

## Data Explanation
The datasets contain information on personnel losses, equipment losses, and the types of aid provided, including:
- Personnel losses: Daily and cumulative military losses, POWs.
- Equipment losses: Counts of various military equipment lost.
- Aid data: Types and monetary values of aid provided.

## Data Cleaning and Transformation
Key steps in data cleaning and transformation included:
- Removing duplicates.
- Handling missing values.
- Data type conversion.
- Aggregating data for better analysis.

## Modeling and Evaluation
We used the ARIMA model to predict future personnel losses based on historical data. The model was evaluated using:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

## Findings and Analysis
- The majority of aid provided is military support.
- Drones account for the largest share of air equipment losses.
- The United States has contributed the most in monetary value of aid.

## Conclusion
The analysis reveals that military aid is the primary focus, with financial assistance also significant. The predictive model provides insights into future losses, but improvements are necessary.

## Future Work
Future research could explore different aspects of the situation or apply similar methods to other conflict scenarios. Continuous updates of data and models are essential for accuracy.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
