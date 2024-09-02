## Credit Risk Analysis: EDA Case Study
### Overview:
This project focuses on assessing the creditworthiness of loan applicants through detailed Exploratory Data Analysis (EDA). By analyzing various data points related to loan applicants, the goal is to manage credit risk effectively and assist financial institutions in making informed decisions regarding loan approvals.

### Project Goals
* Assess Creditworthiness: Determine the likelihood of applicants repaying their loans based on their profiles.
* Manage Credit Risk: Help financial institutions minimize financial loss by identifying high-risk applicants and avoiding loan defaults.
* Business Decision Support: Provide insights that guide the approval or rejection of loan applications.

### Dataset
The project utilizes three key datasets:

1. application_data.csv: Contains client information at the time of loan application, indicating whether they faced payment difficulties.
2. previous_application.csv: Includes data on clients' previous loan applications, with information on whether those applications were approved, canceled, refused, or unused.
3. columns_description.csv: A data dictionary explaining the meaning of the variables in the datasets.

## Analysis Performed
### Outlier Detection
* Income Distribution: Analyzed the income distribution among clients and identified significant outliers.
* Quartile Analysis: Determined that most clients' credit amounts fall within the first quartile.

### Univariate Analysis
* Loan Repayment: Bar charts were used to analyze the distribution of clients who successfully repaid loans (Target = 0) versus those who faced difficulties (Target = 1).
* Income and Gender: Explored income distribution across different genders and identified patterns in credit distribution.

### Bivariate Analysis
* Income vs. Number of Children: Found that income is inversely proportional to the number of children a client has.
* Credit Amount vs. Housing Type: Analyzed the relationship between credit amounts and different housing types, with insights on where banks should focus lending efforts.

### Correlation Analysis
* Age and Credit Amount: Discovered that credit amounts are higher for younger individuals.
* Income and Location: Established that income is generally higher in densely populated areas.

## Key Insights
* Target Demographics: Working women and state servants are ideal candidates for loan approval due to their higher likelihood of successful repayment.
* Risky Applicants: Individuals with loans for purposes like repairs or who live in co-op apartments pose a higher risk of default.
* Approval Strategy: Banks should focus on approving loans for applicants in office apartments or those with previous approvals, as they are less likely to default.

## Conclusion
This EDA provides valuable insights into managing credit risk and supports financial institutions in making data-driven decisions. By understanding the patterns and correlations within the dataset, banks can optimize their loan approval processes, reduce defaults, and enhance profitability.

### Author
Audumbar Awate

### License
This project is licensed under the MIT License - see the LICENSE file for details.
