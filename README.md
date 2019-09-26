# Project_1

## 1) Problem Statement

How to increase the participation rate for SAT and ACT exams among graduates in Alaska.

These are the step taken to solve the problem.

## 2) 2017 Data Import and Cleaning
#### 1. Read In SAT & ACT  Data
#### 2. Display Data
#### 3. Fix any errors you identified
#### 4. Check data types? 
#### 5. Fix Incorrect Data Types
#### 7. Renamed Columns
#### 8. Create a data dictionary

<h1><center>SAT & ACT Data Dictionary 2017</center></h1>

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|ACT 2017| Different states in United States|
|participation_act_17|float|ACT 2017| Participation rates for ACTs in the different states in United States(Units: Example 0.1 = 10%)|
|english_act_17|float|ACT 2017| Average score for English in the different states in United States|
|math_act_17|float|ACT 2017| Average score for Mathematics in the different states in United States|
|reading_act_17|float|ACT 2017| Average score for Reading in the different states in United States|
|science_act_17|float|ACT 2017| Average score for Science in the different states in United States|
|composite_act_17|float|ACT 2017| Average Composite score in the different states in United States|
|state|object|SAT 2017| Different states in United States|
|participation_sat_17|float|SAT 2017| Participation rates for SATs in the different states in United States(Units: Example 0.1 = 10%)|
|evidence-based_reading_and_writing_sat_17|float|SAT 2017| Average score for Evidence-Based Reading and Writing in the different states in United States|
|math_sat_17|float|SAT 2017| Average score for Mathematics in the different states in United States|
|total_sat_17|float|SAT 2017| Average Total score in the different states in United States|

#### 9. Drop unnecessary rows
#### 10. Merge Dataframes

## 3) 2018 Data Import and Cleaning
#### 1. Read In SAT & ACT  Data
#### 2. Display Data
#### 3. Fix any errors you identified
#### 4. Check data types? 
#### 5. Fix Incorrect Data Types
#### 7. Renamed Columns
#### 8. Create a data dictionary

<h1><center>SAT & ACT Data Dictionary 2018</center></h1>

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|final_act_2018| Different states in United States|
|participation_act_18|float|final_act_2018| Participation rates for ACTs in the different states in United States(Units: Example 0.1 = 10%)|
|english_act_18|float|final_act_2018| Average score for English in the different states in United States|
|math_act_18|float|final_act_2018| Average score for Mathematics in the different states in United States|
|reading_act_18|float|final_act_2018| Average score for Reading in the different states in United States|
|science_act_18|float|final_act_2018| Average score for Science in the different states in United States|
|composite_act_18|float|final_act_2018| Average Composite score in the different states in United States|
|state|object|sat_2018| Different states in United States|
|participation_sat_18|float|sat_2018| Participation rates for SATs in the different states in United States(Units: Example 0.1 = 10%)|
|evidence-based_reading_and_writing_sat_18|float|sat_2018| Average score for Evidence-Based Reading and Writing in the different states in United States|
|math_sat_18|float|sat_2018| Average score for Mathematics in the different states in United States|
|total_sat_18|float|sat_2018| Average Total score in the different states in United States|

#### 9. Drop unnecessary rows
#### 10. Merge Dataframes

## 4) Exploratory Data Analysis

### Summary Statistics
- Looking at all the datatypes in the marged dataframe

#### Manually calculate standard deviation
#### Investigate trends in the data
- Which states have the highest and lowest participation rates for the:
    - 2017 SAT?
    - 2018 SAT?
    - 2017 ACT?
    - 2018 ACT?
    
## 5) Visualize the data
#### Use Seaborn's heatmap with pandas .corr() to visualize correlations between all numeric features
- Plot and interpret histograms
  - Participation rates for SAT & ACT
  - Math scores for SAT & ACT
  - Reading/verbal scores for SAT & ACT
  
#### Plot and interpret scatter plots
- SAT vs. ACT math scores for 2017
- SAT vs. ACT verbal/reading scores for 2017
- SAT vs. ACT total/composite scores for 2017
- Total scores for SAT 2017 vs. 2018
- Composite scores for ACT 2017 vs. 2018

#### Plot and interpret boxplots
- Participation Rates
- SAT scores
- ACT scores

#### Pairplot to look for any correlation between different Columns

#### Scatter Plot (ACT Participation vs SAT Participation)
#### Scatter Plot (ACT Participation vs Composite Scores)
#### Scatter Plot (SAT Participation vs Total Scores)

## 6) Plots to support Descriptive and Inferential Section

## Descriptive and Inferential Statistics
#### Summarizing Distributions
#### We generally assuming that data we sample from a population will be normally distributed. Do we observe this trend?
Does This Assumption Hold for:
    - Math
    - Reading
    - Rates
    
#### Estimate Limits of Data
Suppose we only seek to understand the relationship between SAT and ACT participation rates in 2017. 
##### Does it make sense to conduct statistical inference given these data specifically? 
##### Is it appropriate to compare *these* specific SAT and ACT math scores? 
#### Statistical Evaluation of Distributions 

## 7) Outside Research

## 8) Conclusions and Recommendations

##References/Useful Links

http://library.ucmerced.edu/node/10249

https://jupyter-notebook.readthedocs.io/en/stable/examples/Notebook/Working%20With%20Markdown%20Cells.html

https://matplotlib.org/tutorials/introductory/pyplot.html

https://www.dispatch.com/news/20170228/ohio-schools-must-now-give-act-or-sat-to-all-juniors

https://www.testive.com/colorado-sat-change-2017/

https://www.chalkbeat.org/posts/co/2015/12/23/goodbye-act-hello-sat-a-significant-change-for-colorado-high-schoolers/

https://www.edweek.org/ew/section/multimedia/states-require-students-take-sat-or-act.html

https://www.adn.com/alaska-news/education/2016/06/30/students-no-longer-need-national-tests-to-graduate/

https://www.orlandosentinel.com/news/education/os-ne-act-sat-florida-scores-20181024-story.html

https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows

https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/
