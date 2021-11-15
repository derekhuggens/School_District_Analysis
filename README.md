# School District Analysis
##
Overview
###
The purpose of the school district analysis was to help Maria aggregate and report performance trends and patterns of multiple schools to then help guide strategic decisions.

##
Results
###
* How is the district summary affected?

As seen below in Figures 1 and 2: The school district summary was affected by a student count that changed from 39,170 to 38,709 after the Thomas High School 9th grade students were dropped with NaN values. The school count and budget remained the same. After formatting the district summary dataframes to "{.1f}", the post-grade replacement showed that the average math score dropped by 0.1%, the average reading score remained the same, the % passing math decreased by 0.2%, the % passing reading decreased by 0.1%, and the overall passing % decreased from 65.2% to 64.9%.

Figure 1: 
District summary before replacing Thomas High School 9th grader math and reading grades.

![image](https://github.com/derekhuggens/School_District_Analysis/blob/2e88137e338e992c3c2d6585f43a117dd338a6d2/Resources/district_summary_original.PNG)

Figure 2:
District summary after replacing Thomas High School 9th graders' math and reading grades with NaN.

![image](https://github.com/derekhuggens/School_District_Analysis/blob/2e88137e338e992c3c2d6585f43a117dd338a6d2/Resources/district_summary_replaced.PNG)

* How is the school summary affected?

As seen below in Figures 3 and 4: The potential academic dishonesty affected the Thomas High School rows' values within the per school summary dataframe, however, the other 14 schools will remain unnaffected since their respective data values were not manipulated. Thomas High School is still a charter school, it's total student count is 1635, although 461 of its 9th graders' grades were removed, the budget remains the same, and the per student budget as well as the spending ranges per student remains the same until futher notice of strategic changes. 

Standardized test grade value changes of Thomas High School 10th-12th graders after 9th grade removal:
  - Average Math Score: 0.07% decrease.
  - Average Reading Score: 0.05% increase.
  - % Passing Math: 0.08% decrease.
  - % Passing Reading: 0.29% decrease.
  - % Overall Passing: 0.32% decrease.

Figure 3: 
School summary before replacing Thomas High School 9th grader math and reading grades.

![image](https://github.com/derekhuggens/School_District_Analysis/blob/166032441b800a2c55916517800884d610bf679f/Resources/school_summary_original.PNG)

Figure 4:
School summary after replacing Thomas High School 9th graders' math and reading grades with NaN.

![image](https://github.com/derekhuggens/School_District_Analysis/blob/166032441b800a2c55916517800884d610bf679f/Resources/school_summary_replaced.PNG)

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Replacing the ninth graders' math and reading scores did not affect Thomas High School's performance relative to the other schools as the school still sits at the number 2 position when sorting by overall passing percentage.

* How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade
  - Scores by school spending
  - Scores by school size
  - Scores by school type

##
Summary
##
Stuff
