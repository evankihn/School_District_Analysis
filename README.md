# School_District_Analysis

## Purpose 
The focus of our fourth module brought together the basic knowledge we have built so far using python, and programming language through a handful of different envionrments. Through the combination of jupyter notebook as well as the pandas and numpy libraries, we recieved two csv's breaking down a school districts dataset for their student's math and reading test scores. Early practice in the module helped us better understand how to clean, sort, and analyze it to help better understand how our code could effectively translate the numbers and measurments that represent the dataset. Once our challenge began, the emphasis was focused on first cleaning out certain scores that were deemed to be altered and therefore illegitimate due to academic dishonesty. For the entire 9th grade at Thomas High School, math and reading scores would need to be unincluded before further analysis of the district began. 

From there, the purpose of our analysis was to extract and get a good understanding of the numbers each school totaled that would end up representing the entire district. Key variables included total school budget, average math score, average reading score, as well as the percentages of student body at each school that scored a passing grade.


## Development Enviornment
  - Jupyter Notebook 
  - Python (version 3.7)
      - Pandas library 
      - NumPy Library
      

## Analysis 
   - Overview of the School District Analysis 
       - Similiar to what was covered in the purpose above, the beginning of the analysis started with cutting out all of the math          and reading scores from Thomas High School for students who were in the 9th grade. Once the data is cleaned, sorting will          take place similiar to how we did early in the fourth module in order to get the correct breakdown for each school when            it comes to scores, percentages of students with passing scores, as well as district metrics. 
  
   - Results 
       - How is the district summary affected?
           - The district summary is affected because the clean version fo the data takes out the 461 9th graders from Thomas High              School which affect the averages as well as the percentages. In this case, each of the percentages drops as a result              of the changes. 
           
       - How is the school summary affected?
           - By accessing the two images below, we see that school summary is affected when it comes to the percentages for math,              reading, and overall once the 9th graders are removed. Once we subtract them away, and just use the total students                (10th-12th) that will be accounted for, we see a new percentage that jumps Thomas High School into the number two                  spot as we can see in the second image/link.
       
             https://user-images.githubusercontent.com/82420244/125246326-e343f280-e2ae-11eb-90c1-cff23e6e33cc.png
             https://user-images.githubusercontent.com/82420244/125246123-99f3a300-e2ae-11eb-9986-969260298c16.png
             
       - How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the              other schools?
           - As stated in the third bullet point, Thomas High School's overall performance shoots all the way up to number two on              the list, kicking Wright High School out of the top five on the list.
           
       - How does replacing the ninth-grade scores affect the following:
           - Math and reading scores by grade
               - Because Thomas High School ninth-graders are labeled as nan in both reading and math, it creates a void in the                    data and makes Thomas more of an uncomparable outlier because their scores are not legitimate. 
           - Scores by school spending
           - Scores by school size
           - Scores by school type
    
    
## Summary
The four changes that occured to the updated school district analysis begin with each of the three percentages calculated: % Passing Math, % Passing Reading, and % Overall Passing. Each of these saw a decrease of around 0.1%, which is pretty interesting considering the only real other change came from a less than 0.1 decrease in the math score. The reading score stayed pretty much the same, around 81.9, along with the other vairable staying the exact same. 
    
    
    