
# Aggregation Class

### Using a fake dataset of transactions that I create I want to give an example of

- Aggregation
- Feature Engineering (this could be endless)
- Preparation for an RFM or any other analytic tool aggregate on time and/or user (month or week in this case)
- Pandas data manipulation
- Preparation for a hypothetical churn model

### The class will have in input
    - The file
    - format of file (CSV and parquet accepted, but easy implement others)
    - Aggregation type (month or week accepted, but be brave and creative)
    - Select a period start and end (or none)

### And the class will do in order
    - Read the file
    - Create some feature engineering (be inspired from it but follow the business needs and your creativity)
    - Aggregate and do extra feature engineering
    - Create a calendar (weekly or monthly) based on first and last timestamp in the data frame, and will fill each time period with customer's statistic
    - Create a flat historical data frame
    - Save in a specific folder the data frame(s)
