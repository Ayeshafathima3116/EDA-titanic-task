 📊 Exploratory Data Analysis (EDA) - Titanic Dataset

This repository contains my work for **Task 2: Exploratory Data Analysis (EDA)** as part of the internship program. The objective was to perform statistical and visual exploration of the Titanic dataset to understand its structure, trends, and relationships between features.


📁 Files Included

- Titanic-Dataset.csv – Original Titanic dataset
- EDA_analysis.ipynb– Jupyter Notebook with EDA steps and visualizations
- README.md – Description of the task and steps performed


 🛠 Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Plotly (optional for interactive plots)


 🔍 EDA Steps Performed

 1. Data Loading & Overview
- Loaded the Titanic dataset using 'pandas.read_csv()'
- Inspected basic structure using '.info()' and '.head()'

 2. Summary Statistics
- Used '.describe()' to compute measures like mean, median, std, min, max
- Identified missing values and basic distributions

 3. Distribution Plots
- Created histograms for 'Age' and 'Fare'
- Observed skewness and value ranges

4. Boxplots
- Used boxplots to detect outliers in numerical columns
- Found possible outliers in 'Fare'

 5. Correlation Analysis
- Generated a correlation matrix heatmap
- Found that 'Fare'and 'Pclass' had a moderate negative correlation
- Explored relationship between features and 'Survived'

 6. Pairplot (Multivariate Analysis)
- Used 'pairplot' to visualize relationships between multiple numeric features colored by survival status


🧠 Key Insights

- Passengers with higher fare tended to survive more
- Female passengers had a much higher survival rate
- Some features are slightly skewed and contain outliers
- Clear trends based on passenger class and age groups


🎯 Outcome

This task helped me understand how to extract insights from data using statistics and visualization techniques before building machine learning models.

📤 Submission

This repository is submitted as part of my internship program.  
Thank you for reviewing my work!
