# DSI Course for Statistical Learning

## Contents:
1. [Description](https://github.com/rachaellam/dsi-workshop#description)
2. [Learning Outcomes](https://github.com/UofT-DSI/06-statistical_learning#learning-outcomes)
3. [Logistics](https://github.com/UofT-DSI/06-statistical_learning#logistics)
4. [Course Schedule](https://github.com/UofT-DSI/06-statistical_learning#course-schedule)
5. [Grading](https://github.com/UofT-DSI/06-statistical_learning#grading)
6. [Policies](https://github.com/rachaellam/dsi-workshop#policies)
8. [Acknowledgements](https://github.com/UofT-DSI/06-statistical_learning#acknowledgements)

## Description
The course was created by the University of Toronto's [Data Science Institute](https://datasciences.utoronto.ca). This course provides the intuition and skills required to design, implement, test and validate a variety of supervised learning models. We cover the basics of statistical learning including modelling with the goal of prediction versus inference, prediction accuracy and model interpretability trade-off, and the all-important bias-variance trade-off. Each section of this course will cover a unique set of methods used for supervised learning on real data sets.



This course is designed for those who have a degree in something other than Computer Science/Statistics who are looking to enhance their data science skills for their career.

## Learning Outcomes
By the end of the course, students will:
1. Understand, implement and interpret the results from several supervised learning approaches for regression and classification
2. Utilize resampling methods to extract more information from a data set and to choose the best model
3. Perform exploratory data analysis for unsupervised learning
4. Understand what is required for reproducible learning
5. Appreciate the uncertainties associated with model results and the ethical consequences of acting on these results

## Logistics

### Course Contacts
* Instructor: Navona Calarco [navona.calarco@mail.utoronto.ca](navona.calarco@mail.utoronto.ca)
* TA: Julia Gallucci [julia.gallucci@mail.utoronto.ca](julia.gallucci@mail.utoronto.ca)

### Textbook
As a textbook, we will use the second edition (2021) of *An Introduction with Statistical Learning with Applications in R* (ISLR2), written by Gareth James, Daniela Witten, Trevor Hastie, and Robert Tibshirani. This book can be downloaded for free, online, at its [companion website](https://www.statlearning.com/). If preferred, it can also be purchased, or borrowed from the University of Toronto [library](https://librarysearch.library.utoronto.ca/discovery/fulldisplay?docid=alma991106106183406196&context=L&vid=01UTORONTO_INST:UTORONTO&lang=en&search_scope=UTL_AND_CI&adaptor=Local%20Search%20Engine&tab=Everything&query=any,contains,An%20Introduction%20to%20Statistical%20Learning&offset=0) in print or online.

### Technology Requirements
Lectures and tutorials are run synchronously over Zoom. We use R and RStudio throughout the course. It is preferrable to have both installed; however, the RStudio IDE may be accessed via the 
the [Posit Cloud](https://posit.cloud/) if preferred (free account required). We will occasionally use [Posit Cloud](https://posit.cloud/) for collaborative coding. 

### Classes
This is an intensive course. We will have three classes a week for three weeks (i.e., a total of 21 hours over nine classes). Classes are 6 PM - 8 PM EST on Mondays (with the exception of the first class, moved to Tuesday) and Thursdays, and 9 AM - 12 PM EST on Saturdays. Being mindful of online fatigue, there will be one or two brief breaks during each class.

Classes will consist of instruction via prepared slides, and live-coding. All slides will be made available before lectures online. Students should perform coding in real-time, alongside the instructor. Students are encouraged to ask questions at any time. As required, we will use Zoom Whiteboard to work through 'pen and paper'-type questions, and Posit cloud to work through coding puzzles.

### Tutorial
Tutorial sessions on the same date as each class. Tutorials take place from 5 PM - 6 PM EST on Mondays and Thursdays, and 8:30 AM - 9 AM EST and 12 PM - 12:30 PM EST on Saturdays. Tutorial attendance is optional, and organization is unstructured. The tutorial is the best place for questions/issues pertaining to software, homework, and assignments.

## Class Schedule

### Class Topics

| Class | Date                   | Topic                                                                               |  Resources | Chapter |
|--------|------------------------|-------------------------------------------------------------------------------------|------------| --------|
| 1      | Tuesday 21 February    | Regression <br>(linear regression; simple and multiple, others)                     | [Slides]() |
| 2      | Thursday 23 February   | Classification <br>(logistic regression, generative models)                         | |             
| 3      | Saturday 25 February   | Resampling methods, Linear model selection and regularization                       | |                      
| 4      | Monday 27 February     | Beyond linearity <br>(regressions, step functions, generalized additive)            | |                 
| 5      | Thursday 2 March       | Tree-based methods<br>(decision tree; bagging, random forest, etc.)                 | |                      
| 6      | Saturday 4 March       | Support Vector Machines, Survival analysis                                          | |                     
| 7      | Monday 6 March         | Principal Components Analysis, Reproducibility; Ethics; Inequity                    | |                     
| 8      | Thursday 9 March       | Professional Skills - Industry Case Study  <br>(Guest: Ajit Desai, Bank of Canada)  | |                   
| 9      | Saturday 11 March      | Estimation, Testing, and Learning: Review and Practice                              | |                                                  
## Grading Scheme

Grading is based on three components [1] 3 weekly assignments, [2] homework questions (competion only), and [3] class participation. The grading scheme is as follows:

| Assessment       | Number |  Individual Weight | Cumulative Weight
|------------------|--------|--------------------|------------------|
| Assignments      | 3      |  25%               | 75%              |
| Homework         | 5      |  3%                | 15%              | 
| Participation    | NA     |  NA                | 10%              |

**Assignments**

Assignments will cover key statistical concepts and related code implementation. One assignment is assigned per week, for three weeks, for a total of 3 assignments. Assignments will be introduced in class, can be discussed in tutorial, and questions can be ask of the Instructor and/or TA over email. Assignments are due by midnight on Sundays. Please arrange for extensions *in advance* with the Instructor, [Navona](navona.calarco@mail.utoronto.ca). Please email submissions, as an RMarkdown PDF, to the TA, [Julia](julia.gallucci@mail.utoronto.ca), titled `DSI: Assignemtn X, Name`.

Assignment Due-dates
| Assessment        | Content         | Due Date |
| ------------------| ----------------|----------|
| Assignment 1      | Classes 1,2,3   |  Sunday 26 February, by midnight |
| Assignment 2      | Classes 4,5,6   |  Sunday 5 March, by midnight     |
| Assignment 3      | Classes 7,9     |  Sunday 12 March, by midnight    |

**Homework**

For each class (with the exception of the Industry Case Study), one homework question from the ISLR2 textbook will be assigned. The homework question is graded for **completion only** (i.e., an attempted solution receives full marks), and *only 5 questions* are required over the course (i.e., you do not have to submit 3). The homework questions will require writing code in R, and designed to take no more than 20 minutes. Individual feedback is not provided on the weekly homework question by default, but will be discussed in tutorials. Homework questions must be submitted before the beginning of the next class; late submissions will not be graded. Please email submissions, as an RMarkdown PDF, to the TA, [Julia](julia.gallucci@mail.utoronto.ca). Please title emails `DSI: Homework X, Name`.

Homework Links (<u>only 5 required, marked for competion only!</u>)
| Assessment        | Question         | Due Date | 
| ------------------| -----------------|----------|
| Homework week 1   | q1, pg.X         | Thursday 23 February, by 6pm |
| Homework week 2   | q1, pg.X         | Saturday 25 February, by 9am|
| Homework week 3   | q1, pg.X         | Monday 27 February, by 6pm|
| Homework week 4   | q1, pg.X         | Thursday 2 March, by 6pm|
| Homework week 5   | q1, pg.X         | Saturday 4 March, by 9am|
| Homework week 6   | q1, pg.X         | Monday 6 March, by 6pm|
| Homework week 7   | q1, pg.X         | Thursday 9 March, by 6pm|
| Homework week 9   | q1, pg.X         | Sunday 12 March, by midnight |

**Participation**
We hope all members in the course regularly participate. We define participation broadly, and include attendance, asking questions, answering others' questions, participating in discussions, etc.

## Acknowledgements and Contributions
First slides were developed by Simone Collier under the supervision of Rohan Alexander. Slides have been created and modified by Navona Calarco and Julia Gallucci for Winter 2023. This course pulls largely from the book, *An Introduction to Statistical
Learning with Applications in R* (2nd edition, 2021), by Gareth James, Daniela Witten, Trevor Hastie, and Robert Tibshirani.
