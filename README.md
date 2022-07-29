#### Challenge 4: Module 4

# Overview of Project

## Overview of School District Analysis: 

During Module 4, an analysis for a school district was made, where a lot of results came. Before starting the analysis, cleaning the data to avoid any errors in the results was the first step. A lot of common errors appear because data has not been verified and it is difficult to know when you have the final results. The unknown values inside the dataset can modify the final result making them useless. 
In this case, the school board told Maria to clean the data again because they found students from Thomas High School had an academic dishonesty on the results especially in Math and Reading Grades. The board indicated that those values needed to be replaced with NaNs, but keeping the other data intact. The challenge consists in modifying the data and making the complete analysis with the new data, and finally analyzing if that academic dishonesty changed the final results.


## School District Analysis Results: 

The complete analysis was made during the module and the modifications of the grades from Thomas High School during the challenge. The first part involved changing the value in Math and Reading Grades from Thomas High School students to a NaN. Image 1. shows that those values were changed correctly.

###### Image 1. Students data with NaNs.
!

* District Summary
The next part was the creation of the District Summary, where the analysis was repeated using the new data. Image 2. has the dataframe with the first results and Image 3. has the results with the new data. The differences between Images are the decimal number from “% Passing Math”, “% Passing Reading” and “% Overall Passing”. These differences are minimal, if those numbers from the New District Summary are rounded, the results will be similar as the ones in the first District Summary.

###### Image 2. District Summary Results.
!

###### Image 3. New District Summary Results.
!

* School Summary
The other analysis repeated was for the School Summary. In this case, the difference between “% Passing Math”, “% Passing Reading” and “% Overall Passing” are important. The results in “% Passing Math” went from 93.185690 to 66.911315, in “% Passing Reading” went from 97.018739 to 69.663609 and in “% Overall Passing” went from 90.630324 to 65.076453, as can be seen in Image 4. and Image 5. The results went down replacing the values with NaNs in Math and Reading Scores. Therefore, the Overall Passing Percentage went down. 

###### Image 4. School Summary Results.
!

###### Image 5. New School Summary Results.
!

* Thomas High School’s Performance
The analysis based on High Schools was made changing the ninth graders’ math and reading scores. In Image 6, the results from the first analysis can be seen, where “Thomas High School” was at the second place based on the “% Overall Passing”. After doing the analysis for the second time, “Thomas High School” went down. Image 7. shows that the High School is now at the 8th place, from the Bottom to the Top. The change in the results is clearly notorious, the “% Overall Passing ” values went from 90.630324 to 65.076453.

###### Image 6. Top 5 Schools.
!

###### Image 7. New Bottom Schools.
!

* Scores
Math and Reading Scores by Grade
Image 8. and Image 9. show the results after changing the data with NaNs. The first analysis had the incorrect value at the “9th” Grade column, but in this case the value was replaced with “nan”.

###### Image 8. New Math Scores.
!

###### Image 9. New Reading Scores.
!

Scores by School Spending
The analysis was made based on School Spending, where the ranges were “<$586”, “$586-630”, “$631-645” and “$646-675”, as it is shown in Image 10. The comparison between the results of the first and second analysis weren’t notorious. The final results were rounded so it was difficult to see those little differences between them.

###### Image 10. Grades by School Spending.
!

Scores by School Size
The results in the new School Size analysis were quite the same as in the first analysis. The differences of the results weren’t a big deal. The results can be seen in Image 11.

###### Image 11. Grades by School Size.
!

Scores by School Type
In the analysis of School Type, the same happened as in the other two analyses, where the difference wasn’t notorious or relevant for the data. It is important to mention that the difference can be seen just before the decimal point. Image 12. shows the rounded results with no decimal point.

###### Image 12. Grades by School Type.
!


## School District Analysis Summary: 

Some final conclusions made from the analysis involved how the results were affected after modifying the academic dishonesty in the data. The first conclusion radicates on the fact that there wasn’t a notorious change in most of the cases. For example, District Summary Results weren't affected with the NaNs modifications. In fact, the results were the same if the numbers were rounded. The same happened with analyzes by School Size, by School Spending and by Grade. In this case, differences between the first analysis and the second one weren’t relevant for the data in the final results.
On the other hand, the most notorious changes were in the School Analysis.  According to the final grades, those missing values affected the final position of Thomas High School compared to others. Also, when results were shown, wrong values were replaced with NaNs like in “Math and Reading Scores by Grade”.
As it was explained, some values changed notoriously and others didn’t change at all. In conclusion, it can’t be known the dimension of the errors that having incorrect data can make. It is important to be sure that the using data is correct and if it is not, clearing the data is going to be the first step in the analysis.


