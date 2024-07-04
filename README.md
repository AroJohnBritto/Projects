<h3 align = "left">Exploratory Data Analysis (EDA) is a crucial step in data analysis. It helps understand the dataset, uncover patterns, spot anomalies, test hypotheses and check assumptions.</h3>
<h2 align = "left">Step 1: Understand the Dataset</h2>
Always start with identifying the data source and how it's related to the problem you are working on.
Read the dataset using pandas, look at all the columns using `data.head()`, and get some knowledge about the problem you are solving to know if you have the right data for the given problem or not.
<h2 align = "left">Step 2: Inspect the Data</h2>
The next step is to inspect the data. 

-Use pandas `data.info()` to get a concise summary of the Dataframe, including the number of entries, column names, non-null counts and data types.

-Use `data.isnull().sum()` to identify columns with missing values.

-Use `data.describe()` to get statistical summary of numerical columns.

<h2 align = "left">Step 3: Data Cleaning</h2>
The next step is to clean the data.

-Decide how to handle missing values (e.g.,drop rows, fill with mean/median/mode).

-Ensure columns have the correct data types.

-Use `data.drop_duplicates()` to remove duplicate rows.

-Use statistical methods to identify and handle outliers if needed.

<h2 align = "left">Step 4: Data Visualization</h2>
The next step is to visualize the data.


-Visualize the distribution of individual columns using histograms, box plots or bar plots.

-Explore relationships between two variables using scatter plots, correlation matrices or pair plots.

-Explore relationships between multiple variables using pair plots or advanced visualizations like heatmaps.

<h2 align = "left">Step 5: Feature Engineering</h2>
The next step is feature engineering.

-Based on the data and problem context, create new features that might be helpful for analysis.

-If required, convert categorical variables to numerical format using techniques like one-hot encoding.

<h2 align = "left">Step 6: Find the Next Steps</h2>
The next step is to summarize the key findings from the analysis and finding the next steps.

-Summarize the key insights and patterns discovered during EDA.

-Outline the next steps, such as modelling, further data collection or specific analyses based on EDA results.
