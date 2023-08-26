### Analytics of Students Performance and Prediction Using Machine Learning Techniques

### Background 
> In today's world, one of the most crucial choices a student must make is selecting a suitable career choice while in school.  
Undoubtedly, most students often face the problem of choosing the right career path without proper guidance from qualified professional services. They usually mismatch their career path regarding their personality, skills, and interests. In most cases, students are even forced to opt for a career path such as medicine, accounting, or engineering as a result of pressure from family, and friends, and perhaps the greed for high pay.

### Project Overview
> This project focuses on investigating the factors that influence students' academic performance and also builds and train a machine-learning model to make career prediction and recommendation for students based on their academic performance.  

### Data Dictionary 
> The dataset used in this research has the following fields and can be found [here](http://roycekimmons.com/tools/generated_data/exams)
> - `gender` - male/female
> - `race/ethnicity - one of 5 combinations of race/ethnicity
> - `parent_education_level` -  highest education level of either parent
> - `lunch` - whether the student receives free/reduced or standard lunch
> - `test_prep_course` - whether the student took the test preparation course
> - `math` -  exam score in math 
> - `reading` -  exam score in reading 
> - `writing` -  exam score in writing 

### Key InsightS
1: Deduction could be made that, students whose parents have higher educational level tends to perform better than their fellow counterparts with parents of lower educational level.<br>
2: Students who performs better in one subject, tends to also perform better in other subjects.<br>
3: Students who completed the test preparation course have higher marks than the ones who did not, perhaps, the test preparation have significant impact on overall student performance.<br>
4: Only 2 students in which both are females recorded 100% marks in all the 3 subjects. And they all belong to the same race/ethnicity, group E. Also, out of the 2 students, only one of them has completed the test preparation course. They all have their lunch to be in the standard category. They both have their parent educational levels to be in the associate's degree.


### Conclusion 
**Analysis**<br>
This research has shown that, there are different factors responsible for student performance in exams, these factors ranging from; parents level of education, socio-economic factor, preparation for test among others. However, there are some exceptional cases where students with a low parental level of education also recorded good performance. Similarly, some students did not completed their test preparation courses and they scored full marks in all their subjects. Perhaps, these set of students may have their own unique ways for test preparations.

Some students with Socio-economic disadvantage also appears to performed very well, perhaps these categories of students did not allow economic challenges to sabotage their efforts.<br>
Generally, there are many factors responsible for students’ performances and their level of effects differs.<br>
**NB:** There are other factors that can be considered as well, but they were not captured in the dataset. These factors includes type of facilities in school, methods of teaching, access to internet, peer group, hours of study, home lesson, teacher's qualifications and many more. These factors could have significant impact on student performance.

**Application of Machine Learning Techniques**<br>
`Random Forest`, `Logistic Regression` and `Support Vector Machines` algorithms were used to predict the possible career students can pursue beased on their performance across the 3 subject, `Logistic Regression` give the best accuracy of `98.5%`, followed by `Support Vector Machine` with `90.5%` and `Random Forest` with the least accuracy of `88.5%`.

The developed model can take scores for the 3 subjects as imputs, and predict a suitable career path a student should follow based on the student's performance in the 3 subjects.

It is important to note that, the dataset used in this research has its own limitations as only 3 subjects are available with scores which are `math`, `writing` and `reading`. Having more subjects would have help the model to make more career prediction and recommendations based on the available subjects.


