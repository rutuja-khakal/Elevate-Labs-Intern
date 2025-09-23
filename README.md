# Mall Customer Segmentation Dataset

This dataset contains information about customers of a mall, including demographic and purchasing behavior attributes. It is commonly used for **customer segmentation and clustering analysis**.

## Dataset Description

| Column Name            | Description                                                     | Type         |
|------------------------|-----------------------------------------------------------------|--------------|
| CustomerID             | Unique identifier for each customer                              | Identifier   |
| Gender                 | Gender of the customer (Male/Female)                             | Categorical  |
| Age                    | Age of the customer                                              | Numerical    |
| Annual Income (k$)     | Customer’s annual income in thousand dollars                     | Numerical    |
| Spending Score (1-100) | Score assigned by the mall based on customer spending patterns   | Numerical    |

### Additional Features (after cleaning)

| Column Name      | Description                                |
|-----------------|--------------------------------------------|
| AgeGroup         | Categorized age groups: Teen, Young Adult, Adult, Senior |
| IncomeCategory   | Categorized income levels: Low, Medium, High |

## Usage

- Can be used for **exploratory data analysis**, **customer segmentation**, and **visualizations in Power BI, Python, or R**.  
- Ideal for learning and practicing **customer segmentation techniques**.  

## Notes

- Ensure that `Age` and `Annual Income (k$)` are numeric for proper analysis.  
- `AgeGroup` and `IncomeCategory` columns are derived columns for easier segmentation.  
- Dataset can be further cleaned or filtered based on analysis requirements.


