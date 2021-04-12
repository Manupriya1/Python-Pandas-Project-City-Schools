# UCB-Python-Pandas-Project
## School district analysis with Python using Jupyter Notebook

## Overview of the school
I used Pandas and Numpy libraries on Jupyter notebook to analyze school distric data. I used prescarpped datasets. One data set presented students information with their reading and math scores and other data set presented information about schools and the budget allocation to them. As it turned out that one of the schools - Thomas High School has their ninth graders scores altered, so in this analysis the following data has been dropped. 
School: Thomas High School, Grade: 9th, Scores: Math and reading scores. 

The purpose of the analysis is:

- A high-level snapshot of the district's key metrics, presented in a table format
- An overview of the key metrics for each scorschool, presented in a table format 
- Tables presenting each of the following metrics:
    -Top 5 and bottom 5 performing schools, based on the overall passing rate
    -The average math score received by students in each grade level at each school
    -The average reading score received by students in each grade level at each school
    -School performance based on the budget per student
-   -School performance based on the school size 
    -School performance based on the type of school


## Results: The effect of dropping 9th grade score from Thomas high school is as follows:

### How is the district summary affected?
As we can see below, there is not much difference between the results. That indicates the dropped score might not be alterted. 
- With Thomas 9th grade
  <img width="876" alt="district1" src="https://user-images.githubusercontent.com/69255270/114343214-4daf9000-9b12-11eb-9ba2-fb9f0e9e74a0.png">
- Without Thomas 9th grade
<img width="880" alt="district 2" src="https://user-images.githubusercontent.com/69255270/114343218-50aa8080-9b12-11eb-9bf4-d6c4e0621929.png">

### How is the school summary affected?
<img width="876" alt="school district" src="https://user-images.githubusercontent.com/69255270/114345425-8c474980-9b16-11eb-913d-9ad0f248d1fb.png">

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade
Scores by school spending
Scores by school size
Scores by school type

## Summary: 
Four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs:
1. 

