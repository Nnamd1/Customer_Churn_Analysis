CUSTOMER CHURN ANALYSIS
An Exploratory Data Analysis Performed by Nnamdi Leonard

-------------------------------------------------------------------------------------------------------------------
Order Of Execution:
- Understanding the Business Requirement/Goal
- Understanding the Data
- Importation of required Python Libraries and dataset.
- Data Transformation
- Analysis/Modeling processes
- Observation and Recommendation
- Evaluation Procedures

-------------------------------------------------------------------------------------------------------------------
BUSINESS UNDERSTANDING 

A telecommunications company is concerned about the number of customers leaving their land-line business for cable 
competitors. They need to understand who is leaving. Imagine being an analyst at this company and you have to find 
out who is leaving and why.


DATA TRANSFORMATION

The dataset provided is already preprocessed so no need for cleaning. The data in the 'churn' column was converted
to integer to enable the performance of the Logistic Regression in its classification. There was some selection of
required variables from the data, which was then converted from pandas dataframe to a numpy array.

-------------------------------------------------------------------------------------------------------------------
MODELING PROCESSES AND ANALYSIS

- Normalised the data for the independent variables represented by x

- Used the 80%-20% rule to split the dataset for training and testing

- Performed the modeling algorithm and fitted the values of the trained dataset for x and y. And also setting 'C'
which represents regularization to 0.01 in order strenghten the process.

- Conducted a predictive analysis on the test dataset and also the probability of arriving at our prediction for
the classes.

- Deduced the factors contributing to the churn rate and why they do so


-------------------------------------------------------------------------------------------------------------------
OBSERVATION AND RECOMMENDATION:

- Observation and Recommendation are provided in my analysis, do check it out.

-------------------------------------------------------------------------------------------------------------------
EVALUATION:

Curated the most appropriate evaluation procedures for our modeling, in order to measure the correctness of the
predictions therein. These evaluation includes the Jaccard Index and the Confusion Matrix.

THANKS FOR YOUR TIME