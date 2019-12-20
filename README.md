# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: SAT VS ACT PARTICIPATION IN THE NORTHEAST

# TEAM RESPONSIBILITIES:

My Team is Responsible for:
- Implementing strategies to increase participation rates in low participating states
- programmatically interacting with files and directories
- visualizations
- EDA
- working with Jupyter notebooks for development and reporting

# PROBLEM STATMENT:

We want to propose to the ACT INC board different strategies that will increase the participation rates in the North East. We wanto use EDA to take a look at aggregate SAT and ACT participation rates from each state in the United States. Our team will identify different trends across reigons in America that helps us define our problem, low participating states. 

- #### HOW CAN WE USE DATA FROM LOW PARTICIPATING STATES TO ESTABLISH A MARKETING STRATEGY TO INCREASE ACT PARTICIPATION?

---
# EXECUTIVE SUMMARY:

Northeast participation rates for ACT has been on a drastic decline, while Sat Participation has increased over 25% in the last year. As the manager for marketing at ACT inc, I want to figure out why participation in the North East is low compared to a high participation in the SAT. Many different factors have an affect on the participation rates, such as state policy, student demographics, and geographical location. 

Our team wants to use data anlaytical tools, to understand the relationships between the SAT and ACT participation, along with qualatative factors that may influence these relationships. Understanding our data, year to year, will allow us to set forth high expactations for increased participation in 2020. We can pinpoint states to see how standardized tests are implemented, for each respective state.



# Datasets:

#### Provided Data

For this project, you'll have four provided datasets:

- [2017 SAT Scores](./data/sat_2017.csv)
- [2017 ACT Scores](./data/act_2017.csv)
- [2018 SAT Scores](./data/sat_2018.csv)
- [2018 ACT Scores](./data/act_2018.csv)


You can see the source for the SAT data [here](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/), and the source for the ACT data [here](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows). **Make sure you cross-reference your data with your data sources to eliminate any data collection or data entry issues.**

# Additional Data


We can validate our data by comparing our data to the source, which are  2018 state-by-state average results and participation for the SAT, available [here](https://reports.collegeboard.org/sat-suite-program-results/state-results). 2018 ACT state-by-state mean composite scores and participation rates are [here](http://www.act.org/content/dam/act/unsecured/documents/cccr2018/Average-Scores-by-State.pdf) .


---

# DATA DICTIONARY: WHAT ARE WE WORKING WITH? SAT VS ACT:

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**state**|*object*|ACT|The state where the student took either the SAT or the ACT .| 
|**participation_2017_act**|*int*|ACT|The percentage of students(each state) who took the SAT or the ACT|
|**english_2017_act**|*float*|ACT|The average act english score for each state|
|**math_2017_act**|*float*|ACT|The average act math score for each state|
|**reading_2017_act**|*float*|ACT|The average act reading score for each state|
|**science_2017_act**|*float*|ACT|The average act science score for each state|
|**composite_2017_act**|*float*|ACT|The average composite score, totaling math, science, reading, english|

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**state**|*object*|SAT|The state where the student took either the SAT or the ACT .| 
|**participation_2017_sat**|*int*|SAT|The percentage of students(each state) who took the SAT or the ACT|
|**english_2017_sat**|*int*|SAT|The average sat english score for each state|
|**math_2017_sat**|*int*|SAT|The average sat math score for each state|
|**total_sat_2017**|*int*|SAT|The average sat reading score for each state|


---

# FINDINGS:

- #### SAT PARTICIPATION HAS A HIGH INVERSE CORRELATION WITH ACT PARTICIPATION. 
-  #### NORTHEAST STATES TEND TO PREFER THE SAT OVER THE ACT
- #### CT HAS THE HIGHEST ACT SCORES, BUT LOW PARTICIPATION RATE. 
- #### COLORADO HAS HAS SEEN A MASSIVE DECREASE IN ACT PARTICIPATION
- #### PARTICIPATION AND TOTAL SCORES HAVE A STRONG INVERSE RELATIONSHIP
- #### STATE POPULATION HAS TO BE NORMALIZED TO COMPARE


---

# DEPLOYMENT OF STRATEGY:

BY EXAMINING FURTHER DATA, SUCH AS POLITICAL DATA AND STUDENT DEMOGRAPHIC INFROMATION, WE CAN PREDICT PARTICIPATION RATES IN THOSE STATES. THROUGH MY EXPLORATION OF THE DATA, I WAS ABLE TO CONCLUDE THAT THE ACT PARTICIPATION RATES AND THE TOTAL SCORES ARE INVERSELY RELATED. WE CAN ASSUME THAT STUDENTS ARE OF HIGHER INCOME, DUE TO THE ACCESS OF SUPPLEMENTAL MATERIAL. NOW, WE MUST TAKE STEPS TO DEPLOY A STRATEGY THAT WILL TARGET LOW PARTICIPATION STATES. HERE ARE 3 SUGGESTIONS:



- ALIGN WITH STEM INITIATIVE STATES.
- ALLOW FREE ACCESS TO ACT STUDY MATERIALS FOR LOW INCOME STUDENTS IN THE NORTH EAST
- CONSIDER REDESIGNING TEST FORMAT TO MIRROR REAL WORLD CHANGES





# ADDITIONAL RESOURCES ON ACT PARTICIPATION PER STATE:

https://www.chalkbeat.org/posts/co/2015/12/23/goodbye-act-hello-sat-a-significant-change-for-colorado-high-schoolers/

https://www.wfae.org/post/charlotte-area-sat-scores-provide-glimpse-college-prospects#stream/0

http://blogs.edweek.org/edweek/high_school_and_beyond/2018/10/more_than_2_million_students_take_the_sat.html

https://ed100.org/lessons/poverty


