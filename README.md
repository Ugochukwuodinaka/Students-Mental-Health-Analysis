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
- In this analysis, our first insight shall be on the number of students with depression by gender; below are insights I derived from the data: 
- __Gender Distribution:__ From here, one can see that among all students with depression, 29 of them are females (82.86%), and 6 of them are males, accounting for 17.14%. There is quite a disparity between the number of female students reporting depression and that of male students. 
- __Gender Differences in Depression:__ In this research, the percentage of female students with a greater rate of depression was 73.42%, hence indicating that when considering mental health outcomes, there may be some bias based on gender. The finding, therefore, supports other studies in which the likelihood of depression was reportedly greater among females compared to their male counterparts. Such a disparity could be attributed to hormonal factors, societal expectations, and coping styles. 
- __Implications for Mental Health Support:__ The findings of the present study, with a greater prevalence of depression noted in the female student population, call for gender-sensitive mental health support services within educational institutions. Educational institutions need to constitute interventions or targeted support programs ideally suited to deal with the individual challenges faced by female students. Awareness campaigns and outreach efforts aimed at reducing stigma concerning mental health issues, especially in the case of female students, may prove useful.
<br />
<br />

- <img src="images/Students_With%20_Anxiety.jpg" width="250">

- **Number of Students With Anxiety By Gender:**
- This data offers insights into the prevalence of anxiety among students, segmented by gender. Here's an analysis of the data and key takeaways:
- __Gender Distribution:__ The data reveals that out of the total number of students experiencing anxiety, 24 (70.59%) are female, while 10 (29.41%) are male. The majority of students reporting anxiety are female, indicating a gender disparity in anxiety prevalence.
- __Gender Disparities in Anxiety:__ The higher percentage of female students experiencing anxiety aligns with existing research highlighting that females tend to be more susceptible to anxiety disorders compared to males. Societal expectations, hormonal factors, and coping mechanisms may contribute to this gender disparity in anxiety prevalence among students.
- __Implications for Mental Health Support:__ The data underscores the importance of implementing gender-sensitive mental health support services within educational institutions, with a specific focus on addressing anxiety among female students. Targeted interventions, counseling services, and awareness campaigns tailored to the unique needs of female students may be crucial in mitigating anxiety-related challenges.
<br />
<br />

- <img src="images/Students_With%20_Panic_Attack.jpg" width="250">

- **Number of Students With Panic Attack By Gender:**
- The prevalence of panic attacks among students, categorized by gender. Below is an analysis of the findings along with key insights derived from the data:
- __Gender Distribution:__ The data reveals that out of the total number of students experiencing panic attacks, 25 (75.76%) are female, while 8 (24.24%) are male. Female students constitute a majority of individuals reporting panic attacks, indicating a gender disparity in the prevalence of this mental health issue.
- __Gender Disparities in Panic Attacks:__ The higher percentage of female students experiencing panic attacks aligns with existing research indicating that females are more susceptible to anxiety-related disorders, including panic attacks, compared to males. Socio-cultural factors, biological differences, and coping mechanisms may contribute to this gender disparity in panic attack prevalence among students.
- __Implications for Mental Health Support:__ The data underscores the importance of gender-sensitive mental health support services within educational institutions, particularly in addressing panic attacks among female students. Targeted interventions, such as cognitive-behavioral therapy (CBT) and stress management techniques, tailored to the unique needs of female students, may be beneficial in managing panic attacks.
<br />
<br />

- <img src="images/Students_Visited_A_Specialist.jpg" width="250">

- **Number of Students That Visited A Specialist:**
- This data offers insights into the number of students who visited a specialist for mental health treatment, segmented by gender. Below is an analysis of the findings along with key insights derived from the data:
- __Gender Distribution:__ The data indicates that out of the total number of students who visited a specialist for mental health treatment, 5 are female, while only 1 is male. Female students constitute the majority of individuals seeking specialist treatment, suggesting a gender disparity in help-seeking behavior for mental health concerns.
- __Gender Disparities in Help-Seeking Behavior:__ The higher percentage of female students visiting a specialist for mental health treatment aligns with existing research indicating that females are more likely to seek help for mental health issues compared to males. Societal norms, stigma surrounding mental health, and traditional gender roles may influence help-seeking behavior, leading to disparities in accessing specialist treatment.
- __Implications for Mental Health Support:__ The data underscores the importance of addressing barriers to help-seeking behavior, particularly among male students, who may be less likely to seek professional treatment for mental health concerns. Educational institutions should prioritize initiatives aimed at reducing stigma, raising awareness about available mental health services, and promoting a supportive environment where students feel comfortable seeking help.
<br />
<br />

- <img src="images/Mental_Health_By_Marital_Status.jpg" width="300">

- **Students With Mental Health Condition By Students Marital Status:**
- This analysis is on the prevalence of mental health conditions (anxiety, depression, panic attacks) among students, categorized by marital status. Below is an analysis of the findings along with key insights derived from the data:
- __Anxiety:__ Among students who are not married, 27 individuals (the highest count) report experiencing anxiety, while among married students, 7 individuals report anxiety. The higher number of students experiencing anxiety among those who are not married suggests that marital status may influence anxiety prevalence. This finding could be attributed to various factors such as relationship status, social support networks, and stressors associated with romantic relationships.
- __Depression:__ Students who are not married also exhibit a higher prevalence of depression, with 19 individuals reporting depression compared to 16 individuals among married students.
Marital status may impact depression prevalence due to differences in life circumstances, social support, and coping mechanisms between married and unmarried individuals. Unmarried students may experience unique stressors related to academic pressures, career uncertainty, and interpersonal relationships, which could contribute to higher rates of depression.
- __Panic Attacks:__ The data shows that among students who are not married, 23 individuals report experiencing panic attacks, while among married students, 10 individuals report panic attacks. Marital status may play a role in panic attack prevalence, with unmarried students potentially facing heightened stressors related to personal and academic pressures. Factors such as financial concerns, social isolation, and relationship difficulties may contribute to the higher prevalence of panic attacks among unmarried students.
- __Implications for Mental Health Support:__ The data underscores the importance of considering marital status as a potential risk factor for mental health conditions among students.
Educational institutions should develop tailored support programs and interventions that address the unique needs of students based on their marital status. Providing resources for stress management, relationship counseling, and mental health education can help mitigate the impact of marital status on mental health outcomes among students.
<br />
<br />

- <img src="images/Deppression_Anxiety_Panic_Attack_Trend_By_Students_Age.jpg" width="500">

- **Depression, Anxiety and Panic Attack Trend By Students Age:**
- This is an analysis on prevalence of mental health conditions (anxiety, depression, panic attacks) among students, categorized by age. Below is an analysis of the findings along with key insights derived from the data:
- __Anxiety:__ The data reveals variations in the prevalence of anxiety across different age groups. The highest number of students experiencing anxiety is observed at age 18 (14 students), followed by a decline in subsequent age groups.This trend suggests that anxiety prevalence may peak during late adolescence, coinciding with major life transitions such as entering college or university. Factors such as academic pressure, social challenges, and identity formation during this period may contribute to heightened anxiety levels among younger students.
- __Depression:__ The data indicates fluctuations in the prevalence of depression across different age groups. Depression prevalence is highest at age 18 (11 students) and age 24 (6 students), with lower counts observed in intervening age groups. The peak in depression prevalence at age 18 may reflect the challenges associated with the transition from adolescence to adulthood, while the increase at age 24 could be attributed to the stressors of early adulthood, such as career decisions and financial independence.
- __Panic Attacks:__ Similar to anxiety and depression, the data shows variations in the prevalence of panic attacks across different age groups. The highest number of students experiencing panic attacks is observed at age 18 (9 students), with fluctuating counts in subsequent age groups. The peak in panic attack prevalence at age 18 may be linked to the heightened stress and uncertainty associated with the transition to adulthood, including academic demands and social pressures. The decline in panic attack prevalence in older age groups may reflect a reduction in acute stressors or improved coping mechanisms as students mature.
- __Implications for Mental Health Support:__ The data highlights the importance of age-specific interventions and support services to address the mental health needs of students at different stages of development. Educational institutions should implement targeted programs aimed at promoting mental well-being and resilience, particularly during transitional periods such as the transition from adolescence to adulthood. Early identification of mental health issues and timely intervention can help mitigate the negative impact of anxiety, depression, and panic attacks on students' academic performance and overall well-being.
<br />
<br />

- <img src="images/Deppression_Anxiety_Panic_Attack_Trend_By_Students_Year_of_Study.jpg" width="500">

- **Depression, Anxiety and Panic Attack Trend By Students Year of Study:**
- This analysis focuses on the prevalence of mental health conditions (anxiety, depression, panic attacks) among students, categorized by their year of study. Below is an analysis of the findings along with key insights derived from the data:
- __Anxiety:__ The data reveals variations in the prevalence of anxiety across different years of study. The highest number of students experiencing anxiety is observed in Year 1 (14 students), with decreasing counts in subsequent years. This trend suggests that anxiety prevalence may be highest among first-year students, possibly due to the transition to university or college, academic pressure, and social adjustment challenges. As students progress through their academic journey, they may develop coping mechanisms and resilience to manage anxiety, leading to a decline in prevalence in later years of study.
- __Depression:__ Similar to anxiety, the data indicates fluctuations in the prevalence of depression across different years of study. The highest number of students experiencing depression is observed in Year 1 (14 students), with varying counts in subsequent years. The peak in depression prevalence among first-year students may be attributed to the stressors associated with adjusting to a new academic environment, separation from family and friends, and academic demands. 
- __Panic Attacks:__ The data shows variations in the prevalence of panic attacks across different years of study, with the highest number of students experiencing panic attacks in Year 1 (14 students). The peak in panic attack prevalence among first-year students may be linked to the stress and uncertainty associated with transitioning to university or college, including academic expectations, social pressures, and financial concerns. Similar to anxiety and depression, the prevalence of panic attacks tends to decrease in subsequent years of study as students adapt to their academic environment and develop coping strategies.
- __Implications for Mental Health Support:__ The data highlights the importance of providing targeted mental health support and interventions for students, particularly during the transition to university or college. Educational institutions should implement proactive measures to address mental health concerns among first-year students, including orientation programs, peer support groups, and access to counseling services.
<br />
<br />

- <img src="images/Deppression_Anxiety_Panic_Attack_Trend_By_Students_Course_of_Study.jpg" width="550">

- **Depression, Anxiety and Panic Attack Trend By Students Course of Study:**
- This data analysis is on the prevalence of mental health conditions (anxiety, depression, panic attacks) among students, categorized by their course of study. Below is an analysis of the findings along with key insights derived from the data:
- __Anxiety:__ Engineering, BCS (Bachelor of Computer Science), and BIT (Bachelor of Information Technology) students have the highest prevalence of anxiety, with 7, 5, and 5 students reporting anxiety, respectively. Courses that are typically perceived as demanding or rigorous, such as engineering and computer science, may contribute to heightened anxiety levels among students due to academic pressure and workload. It's important for educational institutions to provide support services tailored to the specific needs of students in high-stress programs, including stress management workshops and counseling services.
- __Depression:__ BIT (Bachelor of Information Technology) students report the highest prevalence of depression, with 8 students indicating depression, followed by Engineering and BCS (Bachelor of Computer Science) with 4 and 6 students, respectively. Similar to anxiety, students in courses with heavy academic demands may experience elevated levels of depression. Factors such as competition, high expectations, and workload can contribute to feelings of inadequacy and hopelessness. Educational 
- __Panic Attacks:__ Engineering and BCS students report the highest prevalence of panic attacks, with 5 students each indicating experiencing panic attacks. Like anxiety and depression, panic attacks may be triggered by academic stressors and pressure to perform. The demanding nature of engineering and computer science programs may exacerbate symptoms of panic attacks among students. Proactive measures such as stress management techniques and relaxation strategies can be beneficial for students in managing panic attacks and building resilience.
- __Implications for Mental Health Support:__ The data underscores the importance of targeted mental health support services tailored to the specific needs of students across different courses of study. Educational institutions should prioritize the development of course-specific mental health initiatives, including stress-reduction programs, academic support services, and peer mentorship opportunities. Encouraging open dialogue about mental health within academic departments and providing accessible resources can help mitigate the negative impact of academic stressors on students' mental well-being.
<br />
<br />

## Visuals in Power BI Report:
You can view and interact with this dashboard report [here](https://app.powerbi.com/view?r=eyJrIjoiYTczYzBhNTktNGVlZi00ODk3LTllMmEtODk1YzAzNzMzYTdmIiwidCI6IjdlYzI5NjU5LTNjZjItNGYzZi1hYmIzLWE3MjJlZGY3ZmYyZCJ9).
<br />
<br />
<br />

## Recommendations For Improving The Mental Health Conditions of Students:
- __Increase Awareness and Reduce Stigma:__ Educational Institutions should implement campus-wide mental health awareness campaigns. They should also provide education and training sessions on recognizing signs of mental distress.
- __Enhance Access to Mental Health Services:__ Educational Institutions should increase availability and accessibility of mental health resources on campus. They should ensure affordability and confidentiality of services.
- __Integrate Mental Health into Academic Curriculum:__ Educational Institutions incorporate mental health education into academic curriculum. They can offer workshops on mindfulness and stress reduction.
- __Establish Peer Support Programs:__ Educational Institutions need to develop peer support programs for emotional support. They can also foster a sense of community through peer-led initiatives.
- __Promote Work-Life Balance:__ They should provide resources for time management and prioritization. Flexible scheduling options can also be advocated for.
- __Strengthen Social Support Networks:__ They should facilitate the formation of social support networks, and then foster connections between students and faculty members.
- __Implement Stress Reduction Initiatives:__ Educational Institutions need to offer stress reduction initiatives such as meditation sessions and relaxation workshops. They should also create designated quiet spaces for relaxation.
<br />
<br />

## Thank You For Following Through!
