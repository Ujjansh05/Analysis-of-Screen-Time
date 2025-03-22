# Analysis-of-Screen-Time
Here,We are a person analysing screen time dataset on the google colab 
# Screen Time Analysis

## Project Description

This project analyzes screen time data to understand app usage patterns, notification frequencies, and their relationship with phone unlocks. The analysis aims to uncover insights into user behavior and potential factors influencing screen time.

## Data Source

The analysis is based on a combined screen time dataset (`combined screen Time dataset 1.csv`). This dataset contains information on app usage, notifications, times opened, and phone unlocks over a period of time.

## Process Flow

1.  **Data Loading and Exploration:**
    The data is loaded into a pandas DataFrame (`df`) and initially explored using functions like `describe()`, `head()`, and `columns` to understand the data's structure and summary statistics.

2.  **Correlation Analysis:**
    A heatmap is generated using seaborn to visualize the correlation between different numerical features in the dataset, providing insights into potential relationships between variables.

3.  **Notification and Unlock Relationship:**
    The relationship between the number of notifications received and the number of times a user unlocks their phone is examined by identifying the maximum number of notifications and corresponding unlocks.

4.  **Usage and Notification Visualization:**
    Bar charts are created using plotly.express to visualize app usage and notifications over time, allowing for comparisons across different apps and time periods.

5.  **App Ranking Analysis:**
    The frequency of apps appearing in different ranks (Rank 1, Rank 2, Rank 3) is analyzed and visualized using bar charts, shedding light on app usage patterns.

6.  **Data Preparation for Machine Learning (Optional):**
    Implemented in the current code, the data could be further prepared for potential machine learning tasks by creating dummy variables for app rankings and separating features from the target variable.

7.  **Instagram and WhatsApp Comparison:**
    A focused comparison between Instagram and WhatsApp usage, notifications, and times opened is conducted using line charts, highlighting differences in user behavior for these specific apps.

## Conclusions

Based on the analysis of the screen time data, the following conclusions can be drawn:

*   There appears to be a potential correlation between the number of notifications received and the frequency of phone unlocks. Higher notification counts may be associated with increased phone unlocking behavior.
*   App usage and notification patterns vary across different apps and over time. Certain apps may be used more frequently during specific time periods or exhibit higher notification frequencies.
*   Instagram and WhatsApp show distinct usage and notification trends. Understanding these differences can provide insights into how users interact with these specific platforms.
*   Further analysis could be conducted to explore the impact of specific app features on screen time and user behavior, such as the presence of social interaction elements or addictive design patterns.

## Dependencies

*   pandas==1.5.3
*   numpy==1.24.3
*   matplotlib==3.7.1
*   seaborn==0.12.2
*   plotly==5.13.1

## Usage

To run the code:

1.  Install the required dependencies.
2.  Load the screen time dataset (`combined screen Time dataset 1.csv`) into your Colab environment.
3.  Execute the code cells in the provided Jupyter Notebook.
