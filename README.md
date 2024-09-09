# TITANIC-SURVIVAL-PREDICTION-
Importing Libraries
In this project, I import essential libraries that play pivotal roles in enhancing data manipulation and visualization capabilities:

pandas: A versatile library for data manipulation and analysis, enabling me to handle tabular data structures effectively.
numpy: A fundamental library for numerical operations and computations, empowering me with efficient mathematical operations on arrays.
seaborn: A powerful data visualization library based on matplotlib, simplifying the creation of informative statistical graphics.
matplotlib.pyplot: A widely used library for creating plots and charts, crucial for visualizing my data and analysis results effectively.
Loading Data
My project begins with loading data from CSV files using the pandas library, segregating the data into train and test datasets. These datasets contain crucial information about the Titanic passengers, forming the foundation of my analysis.

EDA (Exploratory Data Analysis)
Engaging in Exploratory Data Analysis (EDA), I embark on a journey of understanding my dataset deeply. Through various visualization techniques, I:

Visualize distributions of key numerical features like age, number of siblings/spouses (SibSp), number of parents/children (Parch), and fare. This helps me uncover trends and identify outliers.
Explore relationships between different variables, potentially revealing correlations that could impact survival predictions.
Data Cleaning
Data cleaning is a pivotal stage in my analysis. In this phase, I:

Address missing values meticulously, strategically choosing methods like imputation to fill in the gaps in my data.
Drop irrelevant columns such as "PassengerId," "Cabin," "Name," and "Ticket," which don't significantly contribute to my analysis.
Engage in feature engineering, crafting new features or transforming existing ones to enrich my dataset. This can lead to improved predictive performance.
