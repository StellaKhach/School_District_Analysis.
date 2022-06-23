# School_District_Analysis Written Report

This analysis starts with importing the two CVS files into the Jupyter notebook. We were asked to complete two deliverables, the first was to replace math scores and ninth grade reading scores.The second deliverable was to repeat the school district analysis. The first deliverable was to see our understanding of the loc method. The first step, we loc the 9th grade students. In the following two steps, we replace the grades for 9th graders to "NaN" for both math and reading. The last step was to use student_data_df.tail(10) and with this we are able to see all the replacements that have been made. 

Deliverable 1 Analysis
https://user-images.githubusercontent.com/92186586/175209981-6d2f4ab4-b604-4362-ad8b-3ffc75cc9cd2.png

As we can see with the above table generated, there are two ninth graders on the table. The scores for those two have been changed to relfect "NaN". We can also see that our filter for only Thomas High School was also applied to this table. We conclude that there were two 9th grade students in the chart that attended Thomas High School.

Deliverable 2 Analysis
This deliverable was checking 5 different metrics. The first was a district summary followed by a school summary. We recalculate the total student count, the average math score and the average reading score. We then calculate the overall math passing rates and the overall english passing rates. In order to count district summary we found the total number of students, the total budget, average math score, average reading score, passing math score, passing reading and overall passing. The second step was counting school summaries. In order to do so, we calculate the school type, total amount of students, the school budget, per student budget, average math and reading score, overall passing score. 

We also wanted to see which schools were the top performing schools. In this case, I used the overall grades being in ascending order which showed which schools had an overall higher passing grades. This distinguished which is a top performing school.

Another matric used was the average reading and math scores for each grade level. It was also narrowed down to specific schools. We saw that there was an overall higher performance at Griffin and Cabrerra High Schools for math. For reading, Griffin and Cabrera were also the top schools with the highest passing grades. 

https://user-images.githubusercontent.com/92186586/175212986-085e44fe-8e2f-45dc-87b1-74344045b787.png



