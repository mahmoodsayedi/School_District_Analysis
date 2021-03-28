# School District Analysis

## Purpose of Analysis

My friend Maria has asked me to help her compute some analysis on the school district that she works in. After compiling all of the relative data relating the both the schools as well as the students, Maria wanted me to look at how replacing the 9th graders scores at Thomas High School would effect the different analyses that we preformed. In order to do both the original analysis and new analysis, I needed to use python's pandas and numpy libraries. Pandas helped me complete most of the analysis while numpy helped me replace the Thomas High School's 9th Graders' scores. The following analysis will be looking in the comparisons between the original analysis and the new analysis.

## Results

### Questions

We are going to look at the following comparisons between two analyses.

1. How is the district summary affected?
2. How is the school summary affected?
3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
4. How does replacing the ninth-grade scores affect the following:
    - Math and reading scores by grade
    - Scores by school spending
    - Scores by school size
    - Scores by school type

### Answers 

1. How is the district summary affected?

    - The only change is a .1% drop in avg math scores between the two analyses
    ![Before_District_Summary](https://github.com/Wall-E28/school_district_analysis/blob/master/Resources/Before_District_Summary.png)
    ![After_District_Summary](https://github.com/Wall-E28/school_district_analysis/blob/master/Resources/After_District_Summary.png)
2. How is the school summary affected?

    - The only change is within Thomas High Schools statistics as both math and reading scores drop. 
    ![Before_School_Summary](https://github.com/Wall-E28/school_district_analysis/blob/master/Resources/Before_School_Summary.png)
    ![BAfter_School_Summary](https://github.com/Wall-E28/school_district_analysis/blob/master/Resources/After_School_Summary.png)
3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

    - Thomas High School's scores fell heavily dropping them from 4th to 7th highest scores in the district
4. How does replacing the ninth-grade scores affect the following:

    - Math and reading scores by grade

        - The 9th grade scores were brought down as Thomas High School 9th graders averaged higher than other schools
        ![Before_Grade_by_School](https://github.com/Wall-E28/school_district_analysis/blob/master/Resources/Before_Grades_by_School.png)
        ![After_Grade_by_School](https://github.com/Wall-E28/school_district_analysis/blob/master/Resources/After_Grades_by_School.png)
    - Scores by school spending

        - The $630 to $644 range saw a drop from 63% to 56% overall passing percentage
        ![Before_Spending_Range](https://github.com/Wall-E28/school_district_analysis/blob/master/Resources/Before_Spending_Range.png)
        ![After_Spending_Range](https://github.com/Wall-E28/school_district_analysis/blob/master/Resources/After_Spending_Range.png)
    - Scores by school size

        - The 1000 to 2000 size schools saw a drop from 91% to 85% overall passing percentage
        ![Before_School_Size](https://github.com/Wall-E28/school_district_analysis/blob/master/Resources/Before_School_Size.png)
        ![After_School_Size](https://github.com/Wall-E28/school_district_analysis/blob/master/Resources/After_School_Size.png)
    - Scores by school type

        - The charter type schools saw a drop from 90% to 87% overall passing percentage
        ![Before_School_Type](https://github.com/Wall-E28/school_district_analysis/blob/master/Resources/Before_School_Type.png)
        ![After_School_Type](https://github.com/Wall-E28/school_district_analysis/blob/master/Resources/After_School_Type.png)

## Summary

The four major changes that occured between the two analyses were:

1. Without the 9th graders' scores, Thomas High School is not as competitive with other charter schools.
2. Without Thomas High School, the overall 9th graders' scores fell.
3. Without the 9th graders' scores, the district summary changes much less than the Thomas High School.
4. While 9th graders at Thomas High School aren't their highest performers, they do balance out the school's scores compared to just looking at 10th-12th graders.
