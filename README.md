# Mini_Project_Sales_Data-Cleaning
Superstore sales analysis data cleaning using excel
step 1: Import data set in to excel power query editor
Step 2: Change data types
          Remove Duplicates
          Remove blank rows
          Trim all text coloumns like product name ,category, states,city etc
          Capitalized each word using relevant coloums
          check null values,error,data types
          change date using date types via locale
step 3: Create a conditional column named Sales_Category
       if [Sales] < 500 then "Low Sales"
        else if [Sales] <= 1000 then "Medium Sales"
        else "High Sales"
step 3 :create discount category column
      if [Discount] = 0 then "No Discount"
      else if [Discount] <= 0.3 then "Low Discount"
      else "High Discount"
step 4 :create a refernce table 
      Average sales analysis
      using group by analysed average sales for low sales, high sale, average discount of sales

  step 5 :creates another table category wise profit analysis
      calculated total profit, average profit, and total sales for category base.
  step 6 : state wise profit analysis
      obtained for total profit, average profit,elected the Total Profit column.
Applied Sort Descending.
Identified the state with the highest total profit from the first row.
This is helped to identify the best-performing state based on total profit.
  
  
      a
