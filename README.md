# FIFA-Player-Performance-Analysis-Model

FIFA Player Analysis - README
This Python code is intended for analyzing FIFA 2018 player data. It performs various data analysis and visualization tasks using popular libraries like Pandas, Matplotlib, Seaborn, and Numpy. Below is an explanation of what each section of the code does:

Data Import and Exploration
The code starts by importing necessary libraries and reading a CSV file named "data-1.csv" using Pandas to create a DataFrame (df).
It prints the shape of the DataFrame, showing the number of rows and columns, and displays the first 5 rows to give you a glimpse of the data.
Data Preprocessing
It checks for missing data using the "missingno" library and creates heatmaps for the first and second halves of the columns.
The code then fills missing values in specific columns with appropriate values, such as means, constants, or strings.
The code sets Pandas options to display a maximum of 100 rows.
It calculates and prints the number of missing values in each column.
Feature Engineering
Several functions are defined to compute specific player attributes like Defending, General, Mental, Passing, Mobility, Power, Rating, and Shooting.
These functions are applied to the DataFrame to create new columns with these attributes.
The resulting DataFrame now has additional columns for player attributes.
Data Visualization
Various plots are created to visualize player data.
It includes distribution plots for player attributes, count plots for preferred foot, pie charts for weak foot distribution, and bar plots for position and overall score distribution.
There are also box plots showing the distribution of overall scores in different popular clubs and countries.
Player Position Classification
The code defines functions to classify players into various positions based on their attributes, such as RB, LB, RWB, LWB, CB, CDM, RDM, LDM, CM, RCM, LCM, RM, LM, CAM, RAM, LAM, RW, LW, RF, LF, CF, ST, RS, and LS.
These functions are applied to the DataFrame to create new columns with binary classification for each position.
Conclusion
The code provides an extensive analysis of FIFA 2019 player data, including data preprocessing, feature engineering, and data visualization.
It also classifies players into different positions based on their attributes.

Furthermore, I've developed a Tableau Dashboard specifically for a FIFA dataset. This dashboard facilitates the analysis of the Manchester United team's performance potential and whether it's a wise choice as a starting team.
