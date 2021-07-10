# School_district_analysis
## Analysis Overview:

The following analysis on school district provides an overview of each school performance based on students' math and reading scores. By analyzing the different aspects of schools, we are hoping to find rovide information that can help strategically allocate budget for up-coming year. 
However, due to the file shows evidence of academic dishonesty for Thomas High School ninth graders, we are asked to replace the math and reading scores for Thomas High School with "NaNs" while keeping the rest of the data intact. You will also given brief comparison of how this data changes affact the overall analysis of the school performance. 

### District Summary:

We have excluded Thomas High School 9th graders from our overall analysis, this changes resulted in slightly lower overall performance. Here are the changes we overserved at the district summary level:
- Total students counts dropped by 461 students.
- Both Average math and reading scores decreased by 0.1
- All of our % of passing scores for math, reading and overall dropped slightly by <1% points.

Overall distric summary comparison is as follows:

1. Original District Summary


2. New District Summary after the data removals:


###  School Summary & Thomas High School’s performance relative to the other schools:

Although removal of the Thomas 9th graders decreased the overall performance a little bit, but it's not significant enough to impact the overall ranking of the school. Thomas high School still ranks as **Top 2**  of overall performance, but this bring the school to the same ranking as Griffin High School, which originally right after the Thomas high scool as No.3. 

- Before the data changes, Thomas high school outranked the Griffin High School on both of passing reading percentage and overall passing percentage. 
- After excluding the 9th graders, Thomas high school fell behind the Griffin High School on their reading passing percentage, and came almost the same on the overall passing percentage based on the new total students count. 
    - At the same time, the math passing percentage gap between Thomas high school and Griffin High School became more obvious than the original data. 

As you coud see from the above summary, the impact of the changes are too small to impact overall performance, and couldn't alter the ranking significantly. 

### Thomas High School Performance changes:

- Before the data removal, Thomas high school summary as the following:
    % Passing Math   	% Passing Reading	  % Overall passing
    93.3	                 97.3	                90.9	

- After the data removal, homas high school summary as the following:
    % Passing Math	   % Passing Reading	  % Overall passing
    93.2	                97.0	               90.6

So, removing the 9th graders from total school performance has decreased overall school performance level. Original 9th graders has definitely positivily impacted each aspects of students performance summary. 

In our analysis, we have also compared the schools in our file by school size, school type and spending ranges per student.

Since we have only removed the math and reading scores of the Thomas High school 9th graders and kept everything else the same:
1. School type summary hasn't got impacted. 

    - "Charter" type of schools performed sigfincantly better than "District" type of schools, and small changes in the data did not impacted the school performance gap by school type. 

        - Charter schools' overall passing score is higher than 90%, whereas the District schools' overall passing poercentage is only 53%.

2. We categorized the school size only by 3 levels: Small (<1000) , medium (1000-2000) and large( 2000-5000). Even after the removal of 9th graders students count, Thomas high school still belong to the medium size. 

    - Although, the removal of the 9th grader has lowered the oevrall passing percentage by 0.05%. But overall performance didn't impacted the schools performance ranking by size, since the medium size school types has the highest overall passing percentage compred to others.

3. Scores size by spending range also dropped slightly since we removed the higher score contributors of 9th graders from the Thomas high school. But the performance rankings by spedning range also didn't changed. Overall passing performances by spending ranges differs more than 10% points per level, so the drop from overall passing of 62.85% to 62.77% would not imapct the performance of schools by spending range. 

4. As for the Math and reading scores by grade: the performance would not change for other grades, since the removal of 9th graders' scores and student counts won't impact any aspects of performances by each grade. 

## Summary:

Removal of the Thomas high school 9th graders scores:

1. Lowered the Thomas high school math and reading passing percentages.

2. Lowered the Thomas high school overall passing percentage, which further closed the gap between Thomas High school and Griffin High School rankings by overall passing percentages.

3. Schools performances by different category that Thomas high school belonged to has lowered in passing percentages, but not significant enough to alter rankings compared to other categories.

4. Thomas High school passing math/reading/overall performance of 9th grade shows up as NANs, we won't be able to compare the 9th graders of the school to other schools.


