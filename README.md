# School_District_Analysis
## Overview of the school district analysis:
### Purpose
The purpose of this analysis is, that the school district asked for a snapshot of survey key metrics by each school compass and school district level.
The main analysis focused on the performance of math and reading percentage and overall scores breakdown several ways in the preparation of school board meeting and asked the school district, however; After the school board reviewed and suspect the school file shows academic dishonesty; specifically reading and Math score for Thomas High School ninth graders and asked the math and reading score of Thomas high school ninth graders replace with NaNs while keeping the rest of the data intact. And the data to be removed and analyzed again for comparison.
 
### Results
- #### 	How is the district summary affected?
 
![orignal school district analysis](https://user-images.githubusercontent.com/107454933/180311242-605e95f2-f6b1-4211-858a-d5213a72f641.png)

Thomas High school was turned in to NaN data and the total student count by subtracting the number of ninth-grade students in Thomas High School from the total student count. Which recalculated the passing math and passing reading percentages, and the overall passing percentage with the recalculated new total student count.

![new school district anaylsis](https://user-images.githubusercontent.com/107454933/180311168-be9236c0-c00d-49b9-91eb-c1bb06ff385c.png)

When comparing the two charts we see the change in student count, average math score, percentage passing math, percentage reading, and percentage overall passing.

- ####	How is the school summary affected?
 
 In the original analysis, Thomas High School started with a 93.27% passing percentage math, 97.30% passing percentage reading rate  90.95%, and  Overall passing percentage rate, which was a concern to the school board as being too high. After calculating the total number of 10ths to 12th grade the student’s passing percentage math, passing percentage reading, and overall passing grade changed respectively69.66%, and 65.08% respectivly That means removing 9th-grade students from the data set had a big impact to change the figure of passing percentage rate of Math, reading and overall.

![per school summary orignal](https://user-images.githubusercontent.com/107454933/180321753-973263e6-adeb-495a-9c02-78dd625d48dc.png)

![per school summary new](https://user-images.githubusercontent.com/107454933/180321716-c324f2c3-a48d-44cd-b597-99c72131ba97.png)

 - #### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
   
   In the original analysis, Thomas High school ranked 2nd in the suspect with the school board.
   
![overall score rate by school](https://user-images.githubusercontent.com/107454933/180325088-aa660564-4794-4948-bde0-ab9acd0bb771.png)

  After adjusting 9th-grade data Thomas High school’s rank dropped on 8th place.
  
   ![overall passing rate by school](https://user-images.githubusercontent.com/107454933/180325150-ce439de4-1133-4d0c-a839-6395f4ac2e10.png)
    
- #### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
   ##### Math and reading scores by grade
In the original analysis, Thomas High school’s 9th-grade average math score wasl	83.590022 and the average reading score was 83.728850 and now the scores replace by NaNs the resulting figure is blowing.

 ![new1 math score](https://user-images.githubusercontent.com/107454933/180337096-a8b29779-21b3-47f4-b287-25466d4b0708.png)  
 
 ![reading score](https://user-images.githubusercontent.com/107454933/180336621-4ed8d703-3944-446a-8664-c45d472e6aae.png)
 
  ##### Scores by school spending
  Thomas High school drops in the $630 - $ 644/ students the differences figure belowing
 
 ![per school summary orignal](https://user-images.githubusercontent.com/107454933/180345637-e5348cc0-b7de-4d50-94a3-09211282d55a.png)
  
  ![per school summary new](https://user-images.githubusercontent.com/107454933/180345684-9e278d92-7c1f-4bce-9e3f-3597307fbbe1.png)
  
   ##### scores by scool size
  Thomas High school size is defined as a medium scool and the 9yh grade impact showing on the figure belowing

![size summary df original](https://user-images.githubusercontent.com/107454933/180348328-c82f104d-8c5a-4a5a-82f9-54e8386c179f.png)

![size summary new](https://user-images.githubusercontent.com/107454933/180348373-42326c38-b4b8-4b4e-b881-08e3df4e8f50.png)


   ##### Scores by school type
A Thomas High school is a Charter school type and the orignal charter school rate and new adjested result diffrent showing below.

![type summary df orignal](https://user-images.githubusercontent.com/107454933/180349020-150405b5-7d60-4599-9fe5-7fa286acd2dd.png)

![type summary new](https://user-images.githubusercontent.com/107454933/180349047-a5748934-fdbd-479f-b163-7f39b6e8d9ee.png)

- ### Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
accoring to adjested  analysis the over all passing rate of Thomas High school Changed on a big difference from 90.94% to 65% and the Thomas High School rate drops from 2nd to 8th in the district of analasis and the avarege passing Math and the Average Reading rate changed and the data of the 9th grade shows NaN in and also the impact shows spending summary result on Thomas High School.


  




