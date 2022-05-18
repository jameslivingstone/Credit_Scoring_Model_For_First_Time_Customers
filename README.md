# Credit_Scoring_Model_For_First_Time_Customers

A Python based analysis which develops an algorithm for credit score calculation based on two datasets.

Fictional Credit Union, and fictional data company.

Payment History and Biographic Data csvs from Kaggle.



Summary of Methodology and Conclusion:

Recent studies have shown that Oklahoma has the 4th lowest average number of credit cards in the country.

The Oklahoma National Credit Union needed a business model for attracting customers who have no credit history.

Flex Data came up with a calculative approach for establishing credit worthiness for first-time applicants.

We have started out with 2 initial datasets: credit_record.csv (1,048,576 rows; 3 columns) and application_record.csv (438,558 rows; 18 rows). 

The first file contains the credit history by month with payment status info for each month and the second file contains the applicants’ biographical information. 

Both datasets have the “ID” column as the common identifier.

There were applicant IDs discrepancies between the 2 datasets that initially needed to be removed.

We Limited the months statuses to no more and no less than 6 months of history.

Assessment in Excel and Python.

Constructed Data Dictionaries.

Run .value_counts() on each of our application data categories.

Validate diversity within each column.

Check for unique and missing values.

Use .describe to get statistical summary.

Use .info and .dtype to understand data types.

Construct evaluation criteria dictionary.

Assign points to each month based on the established criteria.

Group the applicants by ID and calculate the credit score by computing the mean of all months.

Assign points for each of the 6 personal characteristics that we outlined.

Group the applicants by ID and calculate the credit score by computing the mean of all months.

Sum the partial point to obtain the application score.

Merge the 2 datasets by ID and calculate the final score by adding the credit score and application score.

Use matplotlib and seaborn for outputting data plots.

Contrary to our initial hypothesis, when we computed our data we found uniform correlations to credit score as well as negligible variation between different variables held within each category. 

It has become clear that within the scope of our particular population for our data that the credit payment status is superiorly significant in calculating credit score and had the greatest impact when it came to correlation and considerable variation. 
