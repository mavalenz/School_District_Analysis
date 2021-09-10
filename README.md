# School_District_Analysis

## Overview of the school district analysis
### Maria, a city district school data analyst has asks us to help her complete her research and analysis on a number schools in the districe from 9th grade through 10th grade. The school board however, notified us that one of the data files had evidence of academic dishonesty in reading and math grades for Thomas High School. The analysis involves:

1. Exploring the data made available to us:
	- schools_complete.csv
	- students_complete.csv
2. Verifying and cleaning the student data
3. Generating the school district summary which includes:
	- Number of students
	- Number of schools
	- Total budget
	- Student score averages
	- Passing score percentages
4. Generating the school summary which includes:
	- Student count per school
	- Budget per student
	- Score averages per school
	- Passing percentages per school
5. Identifying the high and low performing schools
6. Identifying the average math and reading scores by grade
7. Identifying group scores by school spending
8. Identifying group scores by school type

## School District Analysis Results
### **How is the district summary affected?**
The district summary was not noticably affected by the dishonest grades reported by Thomas High School.
As you can see in the tables below the district summary inclusive of 9th graders data in Thomas High School vs the district summary exclusive
of 9th graders data from Thomas High School remained the same.

*District Summary Inclusive*
![District_Summary_Inclusive](https://github.com/mavalenz/School_District_Analysis/blob/main/Resources/District_Summary_Inclusive.PNG)

*District Summary Exclusive*
![District_Summary_Exclusive](https://github.com/mavalenz/School_District_Analysis/blob/main/Resources/District_Summary_Exclusive.PNG)

### **How is the school summary affected?**
The school summary was affected. After replacing all the 9th graders from Thomas High School's math and reading scores to NaN,
the average math score, average reading score, % passing math, % passing reading and % overall passing values changed incrementally. 

![School_Summary_Exclusive](https://github.com/mavalenz/School_District_Analysis/blob/main/Resources/School_Summary_Exclusive.PNG)

### **How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?**
Replacing the ninth graders scores has affected Thomas High School's performance relative to the other schools negatively. As you will notice
in the tables the average scores has dropped significantly ~80-90% down to ~60%.

### **How does replacing the ninth grade scores affect the following:**
*Math and reading scores by grade*
- The main change here as that you will see for Thomas High School, 9th grade students has a average math and reading scores set as NaN.
 
*Scores by school spending*
- Scores by school spending had no affect. 

*Scores by school size*
- Scores by school size had no affect.	

*Scores by school type*
- Scores by school type had no affect.

## Summary
### In summary, after replacing the ninth graders math and reading scores to NaNs for students at Thomas High School, four changes we noticed were:

1. The average math score for Thomas High School decreased.
2. The average reading score for Thomas High School decreased.
3. The % of students passing math for Thomas High School decreased.
4. The % of students passing reading for Thomas High School decreased.



