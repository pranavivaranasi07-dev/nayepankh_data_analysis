NayePankh Foundation Impact Analysis
Objective: To understand the impact and effectiveness of the various educational programs
NOTE: Since no public dataset for NayePankh Foundation was available, a realistic sample dataset was created based on the Foundation's publicly described educational programs. The analysis demonstrates how data-driven decision making could be applied to measure program effectiveness.

DATA COLUMNS:
  Student ID
  Gender
  Program 
  City
  Attendance 
  Pre Test
  Post Test 

Data Cleaning 
  Replaced whitespaces or empty text with Nan
  Converted text data to Title fonts
  Changed the inconsistencies in the gender field 
  Filled the Na columns (missing values) with median or mode (in the case of text columns)
  Normalized Student Id to look uniform 
  Dropped any duplicate records

Data Analysis 
Questions asked:
  Comparison of Improvement in students in different cities?
  Comparison of Improvement in students in different program?
  Improvement with respect to each gender?
  How does Attendance and Improvement correlate?
  What is the highest participation with respect to program?

Tools used:
  Pandas
  NumPy
  Matplotlib
  Google Colab


Key Metric 
  Improvement: Post Test-Pre Test


Visualization
  Improvement vs City
  Improvement vs Program
  Improvement vs Gender
  Attendance vs Improvement
  Program Distribution 



 


