# dsi-project1
Repository for DSI Project 1
### Project 1: SAT & ACT Analysis
This project is about analysing SAT and ACT dataset (comprising of participation and score data 2017/2018) to get key insights on what are the trends and factors contribute to increased participation rates. The following steps were carried out:
- data import & cleaning
- exploratory data analysis
- data visualisation
- key takeaways and recommendations

#### Problem Statement
The new format for the SAT was released in March 2016. With the given data on the performance of SAT/ACT in year 2017/18, analyse and identify key factors that affect SAT participation and make recommendations on how participation rates can be improved in a state with low participation rate.

#### Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|column name|int/float/object|ACT/SAT|This is an example| 
|state|object|ACT|state name
|act_participation_2017|float|ACT|Participation %
|act_english_2017|float|ACT|English Score (1-36)
|act_math_2017|float|ACT|Math Score (1-36)
|act_reading_2017|float|ACT|Reading Score (1-36)
|act_science_2017|float|ACT|Science Score (1-36)
|act_composite_2017|float|ACT|Average of English/Math/Science/Reading (1-36)
|sat_participation_2017|float|SAT|Participation %
|sat_ebrw_2017|int|SAT|Evidence Based Reading and Writing Score (200-800)
|sat_math_2017|int|SAT|Math Score (200-800)
|sat_total_2017|int|SAT|Total of EBRW and Math
##same set of columns are also used for 2018 data

#### Key takeways and recommendations
Based on the data explorations, it was evident that the increase in SAT participation was due to a state policy change of making it mandatory in states like Colorado, Illinois, Rhode Island and few others. With increase number of test takers from varying skill levels, it is normal that the overall test scores will decline.

The data also shows that participation rate has a huge impact on state average SAT / ACT scores. In any state, the top students on the SAT/ACT are those most eager to take it. The lowest participating states tend to send primarily their best students and have the highest scores.

State chosen: Iowa

The followings are some of the measures that can be considered to increase participation rate:
1. Mandating the completion of the SAT for all high school students.
2. Covering all of part of the exam fees
3. Offering the SAT during regular school hours to make student participation as convenient as possible.

In addition, schools can better prepared their students for the exam by:
4. Offering free test preparation program. eg have access to the Official SAT
Online Course
5. Provide additional academic support for students who may need it

Reference: https://www.hanoverresearch.com/media/Best-Practices-to-Increase-SAT-Participation-1.pdf
