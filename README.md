
# Aggregation Class

### Using a fake dataset of transactions that I create I want to give an example of

- Aggregation
- Feature Engineering (this could be endless)
- Preparation for an RFM or any other analytic tool aggregate on time and/or user (month or week in this case)
- Pandas data manipulation
- Preparation for a hypothetical churn model

### The class will have in input

- The file_name
- The format of the file (CSV and parquet accepted)
- Aggregation type ('month' and 'week' accepted)
- Start and ending period (both optional)

### And the class will do in order

- Read the file
- Make some feature engineering (be inspired from it but follow the business needs and your creativity)
- Aggregate and make extra features engineering
- Create a calendar (weekly or monthly) based on first and last timestamp in the data frame, and fill each time period with customer's statistic (0 if they don't have)
- Create a flat historical data Data Frame
- Save in a specific folder
