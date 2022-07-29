# School_District_Analysis
## Overview of the school district analysis

This project seeks that the board of directors can easily understand the district schools' performances. With the help of the pandas library and the jupyter notebook, it was possible to create DataFrames that allowed us to compare each school by budget, school type, school size, and scores by grade to see which school requires more funding and which one is not doing well. Since the reading and math grades for Thomas High School ninth graders appear to have been altered, that data was eliminated. This report adds some insights on how the results changed after eliminating the altered data.

### Files 

Code: PyCitySchools_Challenge.ipynb

Resources: schools_complete.csv, schools_complete.csv, Images

Analysis: PyCitySchools_Challenge_Report.md

## Results

There is a bulleted list that addresses how each of the seven school district metrics was affected by the changes in the data

After cleaning and filtering the data, we found that the next Data Frames are the ones that represent better the actual situation in the 15 schools of the district. 

### The District Summary

It is important to understand the scope of the data. In the next image, I present the district summary. In this Data Frame, we can see a summary of the most important metrics at a district level. While the first three columns remain the same, the last five had a small change after erasing the math and reading scores from Thomas High School. At a general level, the change doesn't seem relevant but we will dive deep into this analysis with the next Data Frames.

Discrict Summary
![9](https://github.com/DylanMontemayor/School_District_Analysis/blob/main/Resources/Images/9.png)

Per School Summary
![8](https://github.com/DylanMontemayor/School_District_Analysis/blob/main/Resources/Images/8.png)

### High and Low Performing Schools

In the next images, I present two data frames with the top five and bottom five schools in the district. After erasing the altered data, we have that Thomas High School is in the top 5 schools when in the previous analysis we got that it was one of the worst. So, it is very important to have data as accurately as possible. 

Top 5
![7](https://github.com/DylanMontemayor/School_District_Analysis/blob/main/Resources/Images/7.png)
Bottom 5
![6](https://github.com/DylanMontemayor/School_District_Analysis/blob/main/Resources/Images/6.png)

### Math and Reading Scores by grade

In the next images, we can see the average scores per grade. Since we erase the 9th grade for Thomas High School, it is only possible to compare the information of other schools. For the 10th, 11th, and 12th grades we can see the general performance by grade.

Math Scores
![5](https://github.com/DylanMontemayor/School_District_Analysis/blob/main/Resources/Images/5.png)
Reading scores
![4](https://github.com/DylanMontemayor/School_District_Analysis/blob/main/Resources/Images/4.png)

### The Spending Summary

In this Data Frame is interesting to see that having a lower spending per student results in a higher overall passing score and the other way around, higher spending leads to a worst overall passing score. 
![3](https://github.com/DylanMontemayor/School_District_Analysis/blob/main/Resources/Images/3.png)

### The School Size Summary

In this Data Frame, we can see that schools with less than 2000 students tend to have a better overall passing percentage. This is important to the board so they can consider decreasing the number of students per school or increasing the actions taken to ensure the overall performance of the students. 

![2](https://github.com/DylanMontemayor/School_District_Analysis/blob/main/Resources/Images/2.png)

### The School Type Summary

In this Data Frame, we can see that the Charter type of school has a better performance than the district type. In this case, it will be important to see the best practices of the Charter schools and try to replicate some in the District schools. 

![1](https://github.com/DylanMontemayor/School_District_Analysis/blob/main/Resources/Images/1.png)

## Summary

Inaccurate information can lead to mistaken reports and not very good decisions. It is important to have correct data or to be able to clean and detect the data that is not helping our reports. In this case, the Thomas High School math and reading scores for the 9th grade, affect the overall result of the school and also each one of the reports in which this school is taken into consideration. After eliminating the altered data, it changed to be one of the top five performance schools, it helped the overall results of the medium schools, and it helped the overall results of the Charters type schools.
