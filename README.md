
# Foreign Domestic Helpers in Hong Kong

Data Cleaning & Modeling
  - Ensure that all data is assigned to the appropriate data type.
  - Using Pivot feature to Pivot Philipines, Indonesia, Others into two field.
  - Rename the pivot column as "Nationality" and "Count".

Caluculation Fields
 - **Growth Rate:** (SUM([Count]) - LOOKUP(SUM([Count]), -1)) / LOOKUP(SUM([Count]), -1)
 - **Share of Total:** SUM([Count]) / SUM([Total])

Visualization
  Line Chart: Trend
  Stacked Bar Chart
  Pie Chart: Share of Total

**i. Tableau**
<img width="1908" height="940" alt="image" src="https://github.com/user-attachments/assets/13b2f840-b175-4442-a9b7-63becccd5777" />
