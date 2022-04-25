# School_District_Analysis
1.) The Purpose of the School District Analysis
    - The purpose of this project analysis is to combine two sources: one of csv files has school data and other csv file has data about the students from those schools, we were using Jupyter Notebook to make this analysis. We had two data files, (students file) contains everything about the students, theirs name, school, grade on math and reading classes. (school file) contains information about the school district, budget, etc. Both files has the same school name column with those two files we combined them into a DataFrame using Jupyter Notebook to make a clear picture of academic process of each student the file gave us. Now we have a very clean data that is easy to read with our final analysis in this assignment. 

2.) Result
    - The district summary were not affected as much by replacing the 9th grader Thomas High School freshmam with NAn this analysis illustrates the overall data and not just of that one student, it contains the info about school budget, how many schools and students are in this analysis. 
    - The school summary got affected after we made our chances and school scores are now lower than it was before in Thomas High School. Bassically the average score droped from As to Ds because of the false data. 
    - After replacing the 9th graders from math and reading scores with NAn value the result got me surprised because of that the average Thomas High school grade score of all the high school students dropped dramatically low because of the freshmens (from 90% to around 65%). After comparing with other school we can see that Thomas High School students is struggling with their grades. 
    - After replacing the 9th graders the results of math and reading grades for freshmen does not even appear in our updated table. After runing the code Thomas High school 9th graders received a NaN for math and reading grades...
    - The score for school spending the dataframe remains the same, because by the time we run the code, we would have to replace the overall school passing score in the dataframe for 10th - 12th grade students, so in this analysis we do not even count that.
    - In the last section of out code we got two section: the Charter and District and data is  unchanged due to we eliminated already the 9th grade freshmens to a null data, and we replaced our data with only passing grade from students betweeen 10th through 12th grade students. 

 3.) Summary 
    - 1. Firts replacement were made by replacing the 9th graders values with NaN to the all scores of Thomas High School.
      2. grades percentage increased for Thomas high school.
      3. Math score percentage went back from 66% to 93%
      4. Reading score percentage went back from 66% to 97%
      5. In the end, the overall percentage went back from 65% to 90%