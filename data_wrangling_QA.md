1. **What is data wrangling, and why is it important in data science?**
   - **Explanation:** Data wrangling, also known as data munging, is the process of cleaning, transforming, and preparing raw data into a format suitable for analysis. It is essential in data science because raw data often contains errors, inconsistencies, missing values, and other issues that need to be addressed before analysis.
   - **Example:** Suppose you have a dataset containing customer information, including names, addresses, and phone numbers. Data wrangling would involve tasks such as standardizing the format of phone numbers, removing duplicate records, and handling missing values in the address field.

2. **What are some common data quality issues you might encounter during data wrangling?**
   - **Explanation:** Common data quality issues include missing values, duplicate records, incorrect data types, inconsistent formatting, outliers, and errors in data entry.
   - **Example:** In a dataset containing sales transactions, data quality issues may include missing values in the "quantity" column, duplicate entries for the same transaction, and inconsistent date formats across different records.

3. **How do you handle missing values during data wrangling?**
   - **Explanation:** Missing values can be handled by techniques such as imputation (replacing missing values with a statistical measure like mean or median), deletion (removing rows or columns with missing values), or prediction (using machine learning models to predict missing values based on other variables).
   - **Example:** If a dataset contains missing values in the "age" column, you can impute the missing values with the mean age of the dataset or predict missing ages based on other features such as gender or income.

4. **What is the difference between wide and long data formats? When would you use each?**
   - **Explanation:** Wide data format has each variable in a separate column, while long data format has multiple observations per row. Wide format is suitable for analyses involving multiple variables, while long format is preferred for analyses involving repeated measurements or time-series data.
   - **Example:** In wide format, each column represents a variable, such as "temperature," "humidity," and "wind speed," with rows representing different observations or time points. In long format, the same data may be represented with fewer columns, where each row contains multiple observations for a single variable along with an additional column indicating the time point.

5. **How do you deal with duplicate records in a dataset during data wrangling?**
   - **Explanation:** Duplicate records can be identified and removed using techniques such as dropping duplicate rows based on a subset of variables or aggregating duplicate records if they contain additional information.
   - **Example:** If a dataset contains duplicate entries for the same customer in an e-commerce database, you can identify and remove duplicate records based on unique identifiers such as customer ID or email address.

6. **Explain the concept of data normalization and when it might be necessary during data wrangling.**
   - **Explanation:** Data normalization is the process of scaling numeric features to a standard range to ensure that they have a similar scale and distribution. It might be necessary during data wrangling when working with algorithms sensitive to differences in feature scales, such as K-nearest neighbors or neural networks.
   - **Example:** In a dataset containing features such as "age," "income," and "education level," data normalization would involve scaling each feature to have a mean of 0 and a standard deviation of 1 to prevent features with larger scales from dominating the analysis.

7. **What are some techniques for handling outliers in a dataset?**
   - **Explanation:** Techniques for handling outliers include trimming (removing extreme values beyond a certain threshold), winsorizing (replacing extreme values with less extreme values), transformation (applying mathematical transformations such as log or square root), and treating outliers as missing values.
   - **Example:** In a dataset containing housing prices, outliers may include unusually high or low prices for properties. One approach to handling outliers is to winsorize the data by replacing prices beyond the 95th percentile with the value at the 95th percentile.

8. **How do you convert categorical variables into numerical format during data wrangling?**
   - **Explanation:** Categorical variables can be converted into numerical format through techniques such as one-hot encoding (creating binary dummy variables for each category), label encoding (assigning a unique numerical value to each category), or frequency encoding (replacing categories with their frequency of occurrence).
   - **Example:** In a dataset containing a categorical variable like "gender" with categories "male" and "female," one-hot encoding would create two binary variables, one indicating "male" (1 if male, 0 otherwise) and the other indicating "female" (1 if female, 0 otherwise).

9. **What is the role of regular expressions in data wrangling, and how do you use them?**
   - **Explanation:** Regular expressions (regex) are used to search for and manipulate text patterns within strings. In data wrangling, they can be used to extract or replace specific patterns of text, such as dates, phone numbers, or email addresses, from unstructured data.
   - **Example:** In a dataset containing text data, regular expressions can be used to extract email addresses from a string of text by searching for patterns that match the typical format of an email address (e.g., "username@example.com").

10. **Explain the process of data aggregation during data wrangling.**
    - **Explanation:** Data aggregation involves combining multiple data points into a summary statistic, usually performed using grouping operations. It can be used to summarize data at different levels of granularity, such as calculating averages, sums, counts, or other aggregate functions by categories or time periods.
    - **Example:** In a dataset containing sales transactions, data aggregation may involve grouping transactions by product category and calculating the total sales revenue for each category over a specific time period.
