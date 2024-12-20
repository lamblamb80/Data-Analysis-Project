Data Project Rubric: 
Data Analysis with Python (Pandas & Matplotlib)

1. Project Overview 
Objective: Is there a correlation between implantable status and recall status? Are issues with implantable devices more likely to lead to recalls? Rate of recall events for implantable vs. non-implantable devices.

Data Source: https://www.kaggle.com/datasets/vladimirmijatovic/faulty-medical-devices-global-dataset
Large dataset collecting failure events across multiple manufacturers

3. Data Cleaning and Preparation 
Handle Missing Values: Chose not to drop NaN values as I was able to filter by Implantable and Recall statuses 

Data Type Adjustments: Converted dtypes to support merging source dataframes

Feature Engineering: Concatenated company and parent company columns.

4. Exploratory Data Analysis (EDA) 
Descriptive Statistics: Did not include summary statistics (min/max etc) given that dataframe contains textual references only.

Data Visualizations:
Required: One visualization (e.g., line plot) if time-series data is relevant. (DONE)


6. Analysis and Insights
Findings: Implantable devices had lower recall rate than non-implantable devices
This might suggest that more stringent regulatory standards for implant design result in better designed product with lower serious failure rates

7. Conclusion and Recommendations (10 points)
Summarize: Implantable status has no bearing on Recall rate

More stringent regulatory requirements may affect design quality and lower likelihood of device failure. 
Recommendations: Based on findings, suggest actions or further analysis.
More data required on device use, material makeup, lifecycle, etc. 






Features
Description 
links
Define the question


Find a question to answer based on the data you decided to use. 


Read in the Data 
Easy: Read a local file
Import the data locally a csv, excel file ect 


Medium: API call 
Import data from an API 


Hard: Web Scrape 
Scrape data from a website and put it into a DataFrame


Hard: Database 
This would involve building a database and doing a query to pull the data then reading it in. 


Data Cleaning 
You must address missing values 
This can be done many ways. You can remove it or fill it. You can forward fill, back fill, or fill with Mean, Median, or Mode ect.  


You must convert your columns to proper data types. 
Convert your columns to int,
Float, String/Object, etc. 


You must engineer one feature 
Calculate a new column from your data. example:Group ages or scores into categories (e.g., ‘Child’, ‘Adult’, ‘Senior’) or Extract year, month, day, or weekday from a date column.











Exploratory Data Analysis
Provide descriptive stats 
Provide summary statistics (mean, median, min, max) for numerical columns.




Data Visualization 
Make at least one plot from your data. 


Analysis and Insights
State your findings in a markdown cell 
Summarize any patterns observed and address the main project question.


Support your findings in a markdown cell 


Reference specific statistics or plot features to back up findings.


Conclusion and recommendations 
Summarize your findings
Present the main conclusions drawn from the analysis.


Recommendations
Based on findings, suggest actions or further analysis.




