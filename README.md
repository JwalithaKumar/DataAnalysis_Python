# DataAnalysis_Python
Exploratory data Analysis

    Exploratory Data Analysis (EDA) helps in understanding the dataset through various techniques 
    like visualization, summary statistics, and feature relationships
    
   EDA Techniques:
          1.	Checking Basic Information
          •	Use Info()
          
          2.	Checking Missing values
          •	Check null values and drop the rows
          
          3.	Summary Statistics
          •	Use Describe()
          •	Using the IQR Method (Interquartile Range)
          We use the 1.5 × IQR rule:
          
          - Lower Bound = Q1−1.5×IQR
          - Upper Bound = Q3+1.5×IQR
          - Any data point below the lower bound or above the upper bound is an outlier.
          
          4.	Visualization:
          4.1.	Histogram
          What it does?
          •	A histogram shows the distribution of a numerical variable.
          •	It groups data into bins and shows the frequency of values within each bin.
          How it helps in EDA?
          •	Helps understand how values are spread (e.g., normal, skewed).
          •	Detects outliers or unusual patterns.
          •	Shows whether data is uniform, normal, or skewed.
          
          4.2.	Heatmap
          What it does?
          •	A heatmap visualizes correlations between numerical variables.
          •	Uses color intensity to show strength and direction of relationships.
          •	Accepts only Numerical features
           	
           How it helps in EDA?
          •	Identifies strongly related features (e.g., Years of Experience vs. Age).
          •	Helps in feature selection for machine learning.
          •	Detects multicollinearity, which can impact predictive modeling.
          
          4.3.	Boxplot
          What it does?
          •	A boxplot summarizes distribution and detects outliers in numerical data.
          •	It shows median, quartiles (Q1, Q3), and extreme values.
          How it helps in EDA?
          •	Identifies outliers (dots outside whiskers).
          •	Shows spread and skewness of numerical features.
          •	Helps understand data symmetry.
          
          4.4.	Countplot
          What it does?
          •	A count plot shows the count (frequency) of categories in a categorical feature.
          How it helps in EDA?
          •	Helps visualize categorical data distribution (e.g., Male vs Female count).
          •	Identifies imbalanced categories (useful for classification tasks).
          •	Shows patterns in categorical data.
          
          4.5.	Pairplot
          A pair plot is a great way to visualize relationships between multiple numerical variables in a dataset. It creates scatter plots for each pair of variables and histograms for individual variables.
          ________________________________________
          When to Use a Pair Plot?
          •	To identify patterns or trends between variables.
          •	To detect correlations (positive/negative relationships).
          •	To spot outliers in data.
          •	Useful for Exploratory Data Analysis (EDA).
          
          5.	Grouping and Aggregation
          5.1.	Grouping – Groupby 
          5.2.	Segmentation – Filter and do analysis on subset
          5.3.	Aggregation – Combine two or more features and analyze
          6.	Pivot
          Also another type of Aggregation
