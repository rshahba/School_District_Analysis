# School_District_Analysis
City school system proficiency

## Overview of Project
This project analysis the standard test data and student funding in each school in the dostrict to provide insight about performance trends and patterns in school's performance. 

### Purpose
The purpose of this analysis is to assist the school board in making decisions regarding the school budgets and priorities.

## Results
- How is the district summary affected?
    - The distrcit summary is not majorly affected as the number of ninth graders at the Thomas High School account for only 1.18% of the total student in the distrcit.

- How is the school summary affected?
    - The school summary data affects have been insignificant as the affected group is very small compared to the total students in the district.
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    - Thomas High School still rankes as the second top school in the district. The following lists the minor drops in each passing category:
        - Passing Math Percentage: (0.046481)
        - Passing Reading Percentage: (0.29013)
        - Overall Passing Percentage: (0.317688)
#### School Summary before removing the ninth graders at Thomas High School
   ![old](https://github.com/rshahba/School_District_Analysis/blob/main/Resources/old-district.png)
#### School Summary after removing the ninth graders at Thomas High School
   ![new](https://github.com/rshahba/School_District_Analysis/blob/main/Resources/new-district.png)
- How does replacing the ninth-grade scores affect the following:
    - Math and reading scores by grade have been both affected very insignificantly
    - The following metricts have not been affected by replacing the ninth-grade score:
        - Scores by school spending
        - Scores by school size
        - Scores by school type

#### Analysis of the Overal Passing Percentage based on school budget, size, and type:
##### School Budget
   - Data demonstrates that surprisingly, schools with lowr budgets per student have performed better in overal passing percetange (both reading and math)
    ![budget](https://github.com/rshahba/School_District_Analysis/blob/main/Resources/budget.png)
##### School Size 
   - Schools with 1000-2000 students, that are known as medium sized schools, have performed better in both math and reading overal passing percentage
    ![size](https://github.com/rshahba/School_District_Analysis/blob/main/Resources/size.png)
##### School Type
   - Charter schools perform 1.684 times better than District schools in both reading and math percentages
    ![type](https://github.com/rshahba/School_District_Analysis/blob/main/Resources/type.png)
