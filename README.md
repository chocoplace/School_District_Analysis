# **Election_Analysis**

### Overview of the school district analysis: 

The project has the goal to aggregate data  to showcase school performance trends by utilizing the standard test data, student funding and student scores. This analysis will assist the school board and stakeholders in making decisions regarding budget allocation and other important decisions that will impact students. The analysis will highlight the following:

### Resources

Data Source: [Schools_complete](https://github.com/chocoplace/School_District_Analysis/blob/main/Resources/schools_complete.csv).
[Student_complete](https://github.com/chocoplace/School_District_Analysis/blob/main/Resources/students_complete.csv).
[Clean_student_complete](https://github.com/chocoplace/School_District_Analysis/blob/main/Resources/clean_students_complete.csv). *We clean this data set through coding. 

Software: Python 3.7.6, Anaconda 4.10.3, Pandas and Jupyter Notebook 6.3.0, among other technical tools such as Git Bash. 

### Results:

The code for the analysis of the election can be found here [PityCitySchools_Challenge](https://github.com/chocoplace/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb), and the results show the following:

- *How is the district summary affected?*

By replacing ninth graders' scores in math and reading results, the district summary was affected with a decrease in the Average Math Score, % Passing Math, % Passing Reading and the % Overall Passing. As seen on the following tables:

District_Summary_Old
![District_Summary_Old](https://github.com/chocoplace/School_District_Analysis/blob/main/Resources/District_Summary_old.png)

District_Summary_New
![District_Summary_New](https://github.com/chocoplace/School_District_Analysis/blob/main/Resources/District_Summary_new.png)

- *How is the school summary affected?*

By replacing ninth graders' scores in math and reading results, the school summary was affected with a decrease in the Average Math Score, Average Reading Score, and most significatively on the percentage of Passing Math, Passing Reading and Overall Passing. As seen on the following tables:

School_Summary_Old
![School_Summary_Old](https://github.com/chocoplace/School_District_Analysis/blob/main/Resources/School_Summary_old.png)

School_Summary_New
![School_Summary_New](https://github.com/chocoplace/School_District_Analysis/blob/main/Resources/School_Summary_new.png)

- *How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?*

After replacing the ninth graders’ scores, Thomas High School remained on the second place of performance list “5 Top Schools”, the only changes were a decrease in the percentages of Passing Math, Passing Reading and Overall Passing. As seen on the following tables:

Top_5_Old
![Top_5_Old](https://github.com/chocoplace/School_District_Analysis/blob/main/Resources/Top_5_old.png)

Top_5_New
![Top_5_New](https://github.com/chocoplace/School_District_Analysis/blob/main/Resources/Top_5_new.png)


- *How does replacing the ninth-grade scores affect the following:*

   -- Math and reading scores by grade
Overall, no changes reflected. We used the same code to analyze this with the understanding that the ninth grades were replaced by NaN = 0. 

   -- Scores by school spending
Overall, no changes reflected. The number of students stayed the same because the code only replaced the score of ninth graders for NaN=0. 

School_Spending _New

![School_Spending _New](https://github.com/chocoplace/School_District_Analysis/blob/main/Resources/School_spending_new.png)

   -- Scores by school size
Overall, no changes reflected. The number of students stayed the same because the code only replaced the score of ninth graders for NaN=0. 

School_Size _New

![School_Size _New](https://github.com/chocoplace/School_District_Analysis/blob/main/Resources/School_size_new.png)

   -- Scores by school type
Overall, no changes reflected. The number of students stayed the same because the code only replaced the score of ninth graders for NaN=0. 

School_Type _New

![School_Type _New](https://github.com/chocoplace/School_District_Analysis/blob/main/Resources/School_type_new.png)

- Summary: 
The most noticeable changes by replacing the grades of ninth graders of Thomas High School with NaN are:

  -- Percentage of Passing Math on School Summary changed from 93.272% to 66.911%.
  
  -- Percentage of Passing Reading on School Summary changed from 97.308% to 69.663%.
  
  -- Percentage of Overall Passing changed from 90.948% to 65.076%.
  
  -- The district summary stayed the same on Total Students and Total Schools and even though the Average Reading Score did not show any changes, the percentage of Passing reading changed from 86% to 85.7%. 

End
