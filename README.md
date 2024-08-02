# Students Mental Health Analysis
![](images/Student_Mental_Health_Image.jpg)
<br />

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset Overview](#dataset-overview)
- [Tools Used](#tools-used)
- [Visualization in Power BI](#visualization-in-power-bi)
- [Project Analysis](#project-analysis)
- [Visuals in Power BI Report](#visuals-in-power-bi-report)
- [Recommendations For Improving The Mental Health Conditions of Students:](#recommendations-for-improving-the-mental-health-conditions-of-students)
<br />


## Project Overview

### Introduction:
The mental health of students has become a significant concern in educational institutions worldwide. With increasing academic pressure, social challenges, and lifestyle changes, understanding and addressing students' mental health needs have become imperative. This project aims to analyze various factors influencing students' mental health, identify patterns, and provide insights for interventions and support systems. This analysis project could be termed as a statiastical research on the effects of mental health on students' CGPA.


### Objectives:
- Investigate the prevalence of mental health issue of depression among students by demography (gender).
- Investigate the prevalence of anxiety mental health issues among students by demography (gender).
- Investigate the prevalence of mental health issue of panic attack among students by demography (gender).
- Evaluate students response to visiting a specialist by students gender.
- Evaluate students mental health conditions (depression, anxiety, panic attacks), among students by the marital status demography.
- Explore the trend of depression, anxiety, and panic attack mental health issues among students using the demography of age.
- Analyze the trend of mental health issues (depression, anxiety, panic attacks) among students by students year of study.
- Analyze the trend of depression, anxiety, and panic attack mental health issues among students using the students course of study.


### Expected Outcomes:

- Identification of gender disparities in the prevalence of depression among students, providing insights into potential demographic risk factors.
- Analysis of gender-based variations in the prevalence of anxiety among students, contributing to an understanding of mental health disparities.
- Exploration of gender-specific patterns in the prevalence of panic attacks among students, informing targeted interventions and support strategies.
- Evaluation of gender differences in students' response to visiting mental health specialists, potentially uncovering barriers to seeking professional help.
- Assessment of the relationship between marital status and mental health conditions (depression, anxiety, panic attacks) among students, highlighting potential vulnerabilities within specific demographic groups.
- Identification of age-related trends in depression, anxiety, and panic attack prevalence among students, facilitating age-sensitive mental health interventions and support systems.
- Analysis of the association between students' year of study and mental health issues (depression, anxiety, panic attacks), providing insights into the impact of academic progression on mental well-being.
- Examination of the relationship between students' course of study and mental health conditions (depression, anxiety, panic attacks), offering insights into discipline-specific stressors and mental health needs.
<br />
<br />

### Dataset Overview
This dataset containing useful data of 101 students used for this analysis. The dataset comprises of vital information crucial for a deep insight into the contributory factors of demography, social and and environmental factors on students' mental well-being. This Data set was collected by a survey conducted by Google Forms from University students to examine 
their current academic situation and mental health.

This dataset is a CSV file which comprises of a single table named 
Student Mental Health" and was provided by [Quantum Analytics](https://www.quantumanalyticsco.org/). You can click on this [link](Student%20Mental%20health.csv) to preview the raw data file. This dataset is made up of 11 fields and 101 rows of ports data.

Detailed information about the fields in this dataset is provided below for a better understanding of this analysis:
| Table                              | Field                    | Description                            |            
|:-----------------------------------|:------------------------ |:-------------------------------------- |
|Student_Mental_health.csv           | Timestamp                | This field records the date and time when the respondent filled out the survey or questionnaire. It provides information about the timing of data collection and can be used for tracking temporal patterns or trends in mental health responses.    |
|                                    | Choose your gender       | This field captures the gender identity of the respondent. It typically includes options such as male and female. Gender is an important demographic variable that may influence mental health experiences and outcomes     |
|                                    | Age                      | This field records the age of the respondent in years. Age is a crucial demographic variable as mental health issues may vary across different life stages. Younger individuals may face distinct stressors compared to older individuals, and age-related trends in mental health can provide valuable insights for intervention strategies.         |
|                                    | What is your course?     | This field indicates the academic course or program in which the respondent is enrolled. It provides information about the academic domain or field of study pursued by the student, which can influence the types of stressors and challenges they encounter. For example, students in STEM (Science, Technology, Engineering, and Mathematics) fields may face different academic pressures compared to students in humanities or social sciences.         |
|                                    | Your current year of Study| This field denotes the current academic year or level of study of the respondent (e.g., year 1, year 2, year 3, and year 4). Academic progression can impact students' exposure to academic stressors, workload, and social dynamics, which may influence their mental health status.       |
|                                    | What is your CGPA?       | This field represents the Cumulative Grade Point Average (CGPA) of the respondent. CGPA is a measure of academic performance based on the grades achieved in courses over a specified period. Academic performance may be associated with mental health outcomes, as students experiencing academic difficulties may face increased stress and anxiety.       |
|                                    | Marital status           | This field indicates the marital status of the respondent, which include the options: single and married. Marital status can be a significant demographic variable affecting mental health, as individuals in different marital statuses may have varying levels of social support and stressors.        |
|                                    | Do you have Depression?  | This field captures whether the respondent self-reports experiencing symptoms of depression. Depression is a common mental health condition characterized by persistent feelings of sadness, hopelessness, and loss of interest or pleasure in activities. This binary variable indicates the presence or absence of depression symptoms based on the respondent's self-assessment.        |
|                                    | Do you have Anxiety?     | This field indicates whether the respondent self-reports experiencing symptoms of anxiety. Anxiety is characterized by excessive worry, fear, and physiological arousal. Similar to depression, this binary variable denotes the presence or absence of anxiety symptoms based on the respondent's self-assessment.         |
|                                    | Do you have Panic attack?| This field captures whether the respondent self-reports experiencing panic attacks. Panic attacks involve sudden and intense periods of fear or discomfort, accompanied by physical symptoms such as rapid heartbeat, sweating, and shortness of breath. This binary variable indicates the presence or absence of panic attack episodes based on the respondent's self-report.         |
|                                    | Did you seek any specialist for a treatment?| This field indicates whether the respondent sought professional help from a specialist (e.g., psychiatrist, psychologist, counselor) for the treatment of mental health issues such as depression, anxiety, or panic attacks. Seeking specialist treatment is an important indicator of help-seeking behavior and access to mental health services.       |
<br />

### Skills Utilized
1. Data Cleaning
2. Data Modelling
3. Data Visualiziation
4. Descriptive Analytics
5. Analytical Thinking and Problem Solving
6. Communication and Reporting
<br />

### Tools Used
1. Power Query Editor
    - Was used to:
        1. Extract,
        2. Transform,
        4. Load all the datasets for this analysis.
           
2. Power BI (Was used to create reports and dashboard for this analysis)
    - The following Power BI Features were incorporated:
        1. DAX
        2. Quick Measures
        3. Page Navigation
        4. Filters
        5. Tooltips
<br />

### Data Cleaning, Transformation and Loading using MS Sql Server:
- The dataset was sourced clean, though a little transformation was done, i also made sure that the data types of the fields were of the right types and that the fields all reported 100% valid for column quality in Power Query Editor.


**Power Query View**

Power Query Screenshot                                                             |                                
:---------------------------------------------------------------------------------:|
![](images/Power_Query_Editor_Screenshot.png)

You can access the complete Power BI project document [here](STUDENTS%20MENTAL%20HEALTH%20ANALYSIS.pbix).
<br />
<br />

## Data Modelling
No data modelling was required as we had just one table for the analysis.
<br />
<br />

## Visualization in Power BI:
#### Report View
![](images/Students_Mental_Hhealth_Analysis_Dashboard.jpg)
<br />
<br />

### Project Analysis:
From the analysis, i made the following Key findings below:
- The Number of Students: __101.__
- The Average Age of Students: __21.__
- Number of Students With Depression: __35.__
- Number of Students With Anxiety: __34.__
- Number of Students With Panic Attack: __33.__
- Number of Students that Seeked Specialist Attention: __6.__
<br />
<br />

- <img src="images/Students_With%20_Depression.jpg" width="250">

- **Number of Students With Depression By Gender:**
- This aspect of the analysis considers the number of school students with depression by their given gender.
- __Gender Distribution:__ Out of students with depression, 29 are female that is 82. 86% and only 6 are males that is 17. 14%. This depicts a clear cut scenario of how the male gender is more prone to depression as compared to the female gender.
- __Gender Differences in Depression:__ From the collected data, it is found that three percent of the participants have plan to leave their job in the next 6 months. Female students rate their depression level 42% higher than male students in support of other literature indicating that females are more prone to depression than males. This may be attributed to hormone issues, cultural and social influence, as well as masculinity or femininity ways of handling stress.
- __Implications for Mental Health Support:__ Again, the fact that the experiences of depression were slightly higher among female students confirms the need for schools to enhance gender-sensitive provisions for learners’ mental health. There is a need for institutions to provide special studies for female students and conduct sensitization on mental health.
<br />
<br />

- <img src="images/Students_With%20_Anxiety.jpg" width="250">

- **Number of Students With Anxiety By Gender:**
- The data contains information about the trend of anxiety prevalence among students by gender. Here is an overview and main conclusions of the data:
- __Gender Distribution:__ The data obtained indicates that out of the total number of students who are anxious, 24, which is 70.59%, are females, while the rest, 10, are males. These findings suggest that more students who report anxiety are females, foreshadowing a gender imbalance with respect to anxiety prevalence.
- __Gender Inequality in Anxiety Disorder Statistics:__ The more significant percentage of females with anxiety is commensurate with prior research touting that females are generally more prone to anxiety disorders as compared to their male counterparts. This may be a function of differences in societal expectations, hormonal influences, and coping strategies.
- __Implications for Mental Health Support:__ The findings also dictate that there is a pressing need for putting in place gender-sensitive mental health support services within the educational setting, with a special focus on anxiety among female students. Targeted interventions, counselling services, and awareness campaigns play a very critical role in the mitigation of challenges linked to anxiety, by being more responsive to the specific needs of female students.
<br />
<br />

- <img src="images/Students_With%20_Panic_Attack.jpg" width="250">

- **Number of Students With Panic Attack By Gender:**
- Prevalence of panic attacks among students by gender. The following analysis describes the results with key takeaways:
- __Gender-wise distribution:__ The data indicate that out of those students who have ever had panic attacks, 25 represent the female gender, accounting for 75.76%, and 8 represent the male gender, accounting for 24.24%. Female students are the majority reporters of panic attacks; thus, in general, there is a gender imbalance in the manifestation of this mental illness.
- __Gender Differences in Panic Attacks:__ The fact that the percentage of female students suffering from panic attacks is higher corresponds to other research that has already proved females to be more prone to anxiety disorders, such as panic attacks, than their male counterparts. This might be due to socio-cultural factors and biological differences and varied coping mechanisms.
‐ __Implications for Mental Health Support:__ The data underlines how very important the planning of sensitive gender mental health support within educational institutions is in tackling panic attacks amongst the female student population. Tailored interventions, such as CBT and other stress management interventions, may help manage panic attacks, tailored most uniquely to the needs of female students.
<br />
<br />

- <img src="images/Students_Visited_A_Specialist.jpg" width="250">

- **Number of Students That Visited A Specialist:**
- This information details how many students visited a specialist to seek help for mental health treatment, categorized by gender. Following is the analysis of the observation and some important takeaways that can be drawn from this data:
- __Gender Distribution:__ The information shows that, out of the total students who went to see a specialist for treatment of their mental health, 5 are female, whereas only 1 is male. Female students, therefore, has the largest number of patients who seek specialist treatment, hence indicating a gender disparity in help-seeking over concerns on mental health.
- __Gender Differences in Help-Seeking Behavior:__ Considering extant research that has shown females to be more likely to seek help for mental health problems than males, it is not surprising that more females visited a specialist for mental health treatment. These norms set by society, the stigma associated with mental health, and conventional gender roles could be influential in help-seeking and create differences in specialist treatment access.
- __Implications for Mental Health Support:__ These data clearly convey the need to work on deterrents to help-seeking behavior, particularly by outreach to male students who may be least likely to seek out professional treatment for mental health concerns. Reduction of stigma, raising awareness about the availability of mental health services, and creation of a supportive environment where it is easy for students to come out for help must be emphasized by educational institutions.
<br />
<br />

- <img src="images/Mental_Health_By_Marital_Status.jpg" width="300">

- **Students With Mental Health Condition By Students Marital Status:**
- This analysis is focused on the statistics of certain mental health disorders (anxiety, depression, panic attacks) among students, divided by the marriage status. Below is an analysis of the findings along with key insights derived from the data:Below is an analysis of the findings along with key insights derived from the data:
- __Anxiety:__ Among non-married students, 27 students who responded said they sometimes had anxiety while only 7 married students said the same. This points to the fact that marital status could be a determinant of anxiety, probably as a result of relationship status, support, and relationship stress.
- __Depression:__ Single students revealed more depression than married students- 19 out of the students were depressed while 16 students were married. It is proved that marital status affects the probability of depression because of differences in life conditions, social support, and coping strategies. Thus, single students experience academic pressures, employment issues, and relational conflicts.
- __Panic Attacks:__ Of the students who are non-married, 23 of them reported having panic attacks while there were only 10 married students who reported the same. Gender, age, and marital state might also be a factor since unmarried students are more likely to be stressed out, economically troubled, lonely, and in conflict, all of which increase the likelihood of the occurrence of panic attacks.
<br />

- <img src="images/Deppression_Anxiety_Panic_Attack_Trend_By_Students_Age.jpg" width="500">

- **Depression, Anxiety and Panic Attack Trend By Students Age:**
- This is an analysis on prevalence of mental health conditions (anxiety, depression, panic attacks) among students, categorized by age. Below is an analysis of the findings along with key insights derived from the data:
- __Anxiety:__ The picture of anxiety rate varies in students grouped according to age: it is the highest in students of 18 years (14 students), and then it gradually declines among the older students. This peak probably occurs at the end of eighth grade or the start of high school, college, or other transitions that increase the amount of school-related stress. 
- __Depression:__ More specifically, it is highest within the age range of the students that were 18 years; 11 students fall under this age bracket and 6 were 24 years. The one at 18 could have been caused by the transition from childhood to adulthood/adolescence the one at 24 could be brought about by early adulthood which is accompanied by issues like career and finance. 
- __Panic Attacks:__ Again, panic attacks also occur most frequently at 18 (9 students) and then randomly in other groupings of students. Stress and uncertainties that are 18 possibly explain the high rate at a time that is considered to be a transition period. The decrease in older groups can be also attributed to the fact that aged students manage stress better than young ones. 
<br />
<br />

- <img src="images/Deppression_Anxiety_Panic_Attack_Trend_By_Students_Year_of_Study.jpg" width="500">

- **Depression, Anxiety and Panic Attack Trend By Students Year of Study:**
- Based on the data presented in this work, this cross-sectional study investigates how many students of different years have certain mental health disorders (anxiety, depression, and panic attacks).
- __Anxiety:__ The overall anxiety level is highest in Year 1 specifically 14 students have been found to be anxiously attached while the rest of the students had less anxiety levels in later years. This maintains that first-year students receive high anxiety due to the change of setting, academic stress, and accommodating pressures. They therefore come up with ways of dealing with things hence they are less anxious.
- __Depression:__ Depression is also most prevalent in Year 1 with 14 students while it is cyclic in other years. The first one may be explained by the psychosocial stress caused by the first days of an academic term, separation from the home environment, and academic workload.
- __Panic Attacks:__ Clearly, the most number of students experiencing panic attacks is in Year 1 (14) while those in Year two (2), Year three (2), and Year four (1) experience very few. This may be associated with the social pressure that students and particularly women, face as they try to balance between school, social life, work and other financial demands as they adapt to university life.
<br />
<br />

- <img src="images/Deppression_Anxiety_Panic_Attack_Trend_By_Students_Course_of_Study.jpg" width="550">

- **Depression, Anxiety and Panic Attack Trend By Students Course of Study:**
- This analysis seeks to establish how often students develop these mental state disorders (anxiety, depression, panic attacks) depending on their course of study.
- __Anxiety:__ Out of all the groups Engineering (7 students) has the most anxiety followed by BCS (5 students) and BIT (5 students). These rigorous classes probably raise stress because of academically challenging requirements and course content. Schools should provide stress management classes and counselors for students in this category.
- __Depression:__ Depression: BIT students are the most affected by depression by responding 8 numbers of students BCS students are 6 numbers and engineering students are only 4 numbers. Pressure, high academic standards, and competitiveness as well as a heavy workload may lead to depression. Support services are crucial.
- __Panic Attacks:__ From among the engineering and BCS students, a total of 5 students said that they have had panic attack at least once. Such rigorous programs could bring on panic attacks. Employment education in stress control and stress reduction can be beneficial.
- __Implications for Mental Health Support:__ There is thus a clear need to avail specific mental health services for the learners taking arduous classes. These should be course-specific activities such as stress busting, help in course work and buddy system. Preventable academic stress consequences can be solved through mental health promotion and proper resource availability.


<br />
<br />

## Visuals in Power BI Report:
You can view and interact with this dashboard report [here](https://app.powerbi.com/view?r=eyJrIjoiYTczYzBhNTktNGVlZi00ODk3LTllMmEtODk1YzAzNzMzYTdmIiwidCI6IjdlYzI5NjU5LTNjZjItNGYzZi1hYmIzLWE3MjJlZGY3ZmYyZCJ9).
<br />
<br />
<br />

## Recommendations For Improving The Mental Health Conditions of Students:
- __Increase Awareness and Reduce Stigma:__ Educational Institutions should come up with intensive mental health awareness across the campuses. They should also arrange education and training session in order to help the colleagues identify signals of mental problems.
- __Enhance Access to Mental Health Services:__ The outcome implies that Educational Institutions should make mental health services more available and accessible on the campus. They should also guarantee the cost and secrecy of the services.
- __Integrate Mental Health into Academic Curriculum:__ Mental health education is adopted into the curriculum of Educational Institutions. With these attributes, they can present seminars focusing on mindfulness and diminishing stress.
- __Establish Peer Support Programs:__ Educational Institutions should implement peer support programs for emotional support. They can also create the feeling of the community through peers’ actions and events.
- __Promote Work-Life Balance:__ They should offer information on how to manage time as well as prioritization schedules. The other arrangements that can also be advocated for include;
- __Strengthen Social Support Networks:__ They should help the formation of social support network, and after that, help the students and the faculty members know each other.
- __Implement Stress Reduction Initiatives:__ Educational Institutions should provide those stress relief programs which include; yoga classes, and stress relieving seminars. They should also come up with odd number quiet places for resting.
<br />
<br />

## Thank You For Following Through!
