# Multinational-Retail-Store-Analysis
This is Analysis of Multinational Retail Store using Python & its library (Pandas, Numpy, Seaborn , Matplotlib, scipy).
In this initially Data is loaded along with required Python Library
First i have Done Some EDA on a Dataset to check for Missing value, Outliers, Data Cleaning is done
Then after Detecting Missing value & outliers i have removed them using various techniques.
After EDA i have use concept of CLT (Central limit Theorem) & Confidence Interval to check for Purcahsing pattern Gender wise, MArital Status & Age Group wise.
Along with it i have done Visualization using various charts for Univariate,Bivariate plots such as Histogram, Barchart,Heatmap are used to check for pattern,frequency and correraltion pattern
in a dataset.
After that i have provided Businees Insight from Graphical & Non-Graphical which were completely Data Driven from the above Data set.
in the end i have provided Recommendation which can be used to increase Sale for Particular Gender,Age group , Marital Status


Business Problem

The Management team at Retail Store  wants to analyze the customer purchase behavior (specifically, purchase amount) 
against the customer’s gender and the various other factors to help the business make better decisions.
They want to understand if the spending habits differ between male and female customers: Do women spend more on Black Friday than men? 
(Assume 50 million customers are male and 50 million are female).

User_ID:	User ID
Product_ID:	Product ID
Gender:	Sex of User
Age:	Age in bins
Occupation:	Occupation(Masked)
City_Category:	Category of the City (A,B,C)
StayInCurrentCityYears:	Number of years stay in current city
Marital_Status:	Marital Status
ProductCategory:	Product Category (Masked)
Purchase:	Purchase Amount

Defining Problem Statement and Analyzing basic metrics.
Observations on shape of data, data types of all the attributes, conversion of categorical attributes to 'category' (If required), statistical summary
Non-Graphical Analysis: Value counts and unique attributes ​
Visual Analysis - Univariate & Bivariate
For continuous variable(s): Distplot, countplot, histogram for univariate analysis
For categorical variable(s): Boxplot
For correlation: Heatmaps, Pairplots
Missing Value & Outlier Detection 
Business Insights based on Non- Graphical and Visual Analysis
Comments on the range of attributes
Comments on the distribution of the variables and relationship between them
Comments for each univariate and bivariate plot
Answering questions
Are women spending more money per transaction than men? Why or Why not?
Confidence intervals and distribution of the mean of the expenses by female and male customers 
Are confidence intervals of average male and female spending overlapping? How can Walmart leverage this conclusion to make changes or improvements?
Results when the same activity is performed for Married vs Unmarried 
Results when the same activity is performed for Age 
Final Insights - Illustrate the insights based on exploration and CLT
Comments on the distribution of the variables and relationship between them
Comments for each univariate and bivariate plots
Comments on different variables when generalizing it for Population
Recommendations 
Actionable items for business. No technical jargon. No complications. Simple action items that everyone can understand
