##
Titanic EDA : Exploratory Data Analysis 

Importing Libraries
pandas, numpy for data handling
matplotlib, seaborn for visualization
Reading Data

The Titanic training dataset is loaded into a pandas DataFrame.

🔍 **Initial Exploration**
• Data structure overview
• Summary statistics
• Detection of missing data

🧹 **Missing Data Handling**
• Dropped the Cabin column due to excessive missing values
• Filled missing Age values using average age by passenger class (Pclass)
• Dropped the row with missing Embarked value

📉 **Data Visualization**
• Survival rate comparisons using barplots and histograms
• Visual patterns among features like Sex, Pclass, and Age

📝 **Feature Engineering**
• Conversion of categorical variables (e.g., Sex, Embarked) into numerical dummy variables
