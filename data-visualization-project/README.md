# PISA Data Exploration
## Dataset
PISA is the OECD’s program for International Student Assessment. Every three years, it tests 15-year-old students from all over the world in reading, mathematics and science. The tests are designed to gauge how well the students master key subject in order to be prepared for real-life situations in the adult world. 
The dataset can be found in (https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisa2012.csv.zip.) with feature documentation available in (https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisadict2012.csv.)

In this project, I’m going to explore how familiarity with different math concepts may affect the math grade. Also, I’m going to investigate if other variables like OUTHOURS (Out-of-School Study Time) and  ESCS (Index of economic, social and cultural status) have a relationship with familiarity level with different math concepts in addition to the math grade. 
Lastly, I’d like to investigate familiarity level with math grade and ESCS for five countries close to my country. These countries are (Tunisia, Jordan, Qatar, Israel, Turkey, United Arab Emirates)

## Summary of Findings
In the exploration, I found there is a moderate relationship between students’ math grades and familiarity with math concepts. Moreover, I found that study time after school has no effect on both students familiarity and students math grades as correlation plots show. On the other hand, Index of economic, social and cultural status has a moderate correlation with students’ math grades and weak relationship with math concepts familiarity. 
In addition, I’d like to mention that I don’t use FAMCON variable to represent familiarity with math concepts, but instead I calculated familiarity from students answers in these variables ().I did this by giving each answer an integer number and then sum all these numbers per students. The output was a variable called familiarity degree in mathematical concepts (fm_degree_total). I confirmed that the correlation coefficient of fm_degree_total vs. PVMATH is very close to the correlation coefficient of FAMCON vs. PVMATH
Because I’m from a middle east country, I’d like to look at students math grades in six countries close geographically to my country, and plot ESCS, Students familiarity, study time after school, and math grade by them. These countries are (Tunisia, Jordan, Qatar, Israel, Turkey, United Arab Emirates). 
For the six countries I chose, I found that students from Isreal has the highest median in math grade, while displaying math grades by ESCS for the selected countries, we will see that for all ESCS group except the lowest and the highest group, Turkish students have the highest math grade median comparing to students from other countries, and there are no participants from Turkey country fall in lowest and the highest ESCS group. 


## Key Insights for Presentation
In my presentation, I focused to present the most familiar math concepts, correlation between math grades and three variables (Familiarity, study time after school, and ESCS (Index of economic, social and cultural status). Also, I chose to present the correlation between Familiarity and both study time after school and ESCS. 
Then, I present students math grade grouped by both variable Familiarity level and ESCS.  Also, I present Math grade grouped by gender and familiarity degree in math in another plot. Finally, I plot math grades by (familiarity degree, OUTHOURS, ESCS) for the selected six countries 


## Resources:
- Data Visualization part at Udacity nano degree course
-	https://towardsdatascience.com/why-and-how-to-use-pandas-with-large-data-9594dda2ea4c






