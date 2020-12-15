# School_District_Analysis

## Background

For this module, we analyzed 2 interlinked datasets on Schools and Students to help drive meaningful insights into improving facilities within schools based on test results and also with budget allocation. The school dataset comprised of :

        School ID, 
        School Name ,
        School Type (Public of Charter) , 
        Number of students currently enrolled in the school
        Budget allocated for the running of the school.
        
The Student dataset comprised of :

        Student ID,
        Student Full Name,
        Gender (M or F),
        Grade (9th,10th,11th,12th),
        School Name,
        Reading scores,
        Math scores secured by the student.
        
## Overview 

This analysis was performed on 39,170 students belonging to 15 different schools. The student dataset comprises of students from the 9th,10th,11th and 12th grade and the marks scored by these students. This dataset helped analyze the best performing schools in each grade based on scores of students within that school. It also helped calculate the average scores by school and by grade. Analysis of this dataset would help government officials to make updates to already assigned budgets based on the need of the school. This dataset could also help analyze if any one gender outbeat the other gender across schools.

## Results 

As part of the analysis, a small subset of students were removed from the analysis. The 9th Graders from Thomas High School were excluded from the analysis and below are some observations from comparing the results of the full subset vs a slightly smaller subset :

* Effect on District Summary: There were minimal to no updates on the Math,Reading,Math and Reading pass percentages in the district summary analysis. All differences were less than 1%. This seems accurate since the number of 9th graders in Thomas High Schools was less than 1% of the total student dataset.

* Effect on School Summary:   Since there were no changes to the data of students belonging to other schools, the school summary analysis only changed for Thomas High School. The overall pass percentage dropped by over 35%

* Based on the data provided, it appears that either the 9th graders at Thomas High School were either over achievers or the scores of these students were manipulated. Excluding the 9th graders from the analysis caused a steep drop in the pass percentages in the school

* Exclusion of Thomas High school 9th graders had no impact on the Math and Reading scores within other grades of the same school and also from other schools

* No impact to the performace by school type considering less than 1% of the data was excluded from the analysis

* There was no impact on the spending by school size since we only excluded the scores from calculations but the students were still present within the schools dataset. Hence the total school size did not have an impact 

## Summary
 
* The overall Math,Reading,Math and Reading pass percentages across all schools and all the students did not change significantly after excluding the 9th graders from     Thomas High School 
* The percentage of students from Thomas High School that passed Math dropped by approxiamtely 26% after exluding the 9th graders
* The percentage of students from Thomas High School that passed Reading dropped by approxiamtely 26% after excluding the 9th graders
* The percentage of students from Thomas High School that passed both Math and Reading dropped by approxiamtely 35% after excluding the 9th graders
* Thomas High School which was among the top 3 schools prior to the exclusion of 9th graders, did not feature in the top 5 schools after the exclusion was done



    
    


