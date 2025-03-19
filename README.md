# EDA and Preprocessing

## Objective
The goal of this project is to perform exploratory data analysis (EDA) and data preprocessing to improve data quality for machine learning models.

## Steps Involved

1. **Data Exploration**  
   - Check unique values in each column.  
   - Perform statistical analysis and rename columns if needed.

2. **Data Cleaning**  
   - Handle missing and inappropriate values.  
   - Replace age value `0` with NaN and treat missing values using median/mode.  
   - Remove duplicate rows.  
   - Identify and treat outliers using the IQR method.

3. **Data Analysis**  
   - Filter data where age > 40 and salary < 5000.  
   - Create a scatter plot for Age vs. Salary.  
   - Count and visualize the number of people from each place.

4. **Data Encoding**  
   - Convert categorical variables to numerical values using Label Encoding and One-Hot Encoding.

5. **Feature Scaling**  
   - Apply StandardScaler and MinMaxScaler for feature scaling.

## Output
- The cleaned dataset is saved as `cleaned_employee_dataset.csv`.
- Data is preprocessed and ready for machine learning applications.

### Note
This project ensures better data quality, making it more suitable for machine learning tasks.

