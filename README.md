# Machine Learning Pipeline-Hr_analytics
 
This is a machine learning Pipeline using a HR analytics data.
A training institute which conducts training for analytics/ data science wants to expand their business to manpower recruitment (data science only) as well. 
 
Company gets large number of signups for their trainings. Now, company wants to connect these enrollees with their clients who are looking to hire employees working in the same domain. Before that, it is important to know which of these candidates are really looking for a new employment. They have student information related to demographics, education, experience and features related to training as well.
 
To understand the factors that lead a person to look for a job change, the agency wants you to design a model that uses the current credentials/demographics/experience to predict the probability of an enrollee to look for a new job.

Data Dictionary 
VARIABLE                             DESCRIPTIONENROLLEE_ID.            UNIQUE ID FOR ENROLLEECITY                       CITY CODECITY_DEVELOPMENT_INDEX       DEVELOPEMENT INDEX OF THE CITY (SCALED)GENDER                   GENDERRELEVENT_EXPERIENCE      RELEVENT EXPERIENCEENROLLED_UNIVERSITY      TYPE OF UNIVERSITY COURSE ENROLLED IF ANYEDUCATION_LEVEL          EDUCATION LEVELMAJOR_DISCIPLINE         MAJOR DISCIPLINEEXPERIENCE               TOTAL EXPERIENCE IN YEARSCOMPANY_SIZE             NO OF EMPLOYEES IN CURRENT EMPLOYER'S COMPANYCOMPANY_TYPE             TYPE OF CURRENT EMPLOYERLAST_NEW_JOB       DIFFERENCE IN YEARS BETWEEN PREVIOUS JOB AND CURRENT                TRAINING_HOURS      TRAINING HOURS COMPLETEDTARGET            0 â€í NOT LOOKING FOR JOB CHANGE, 1 â€í LOOKING FOR A                               JOB CHANGE

 

Note that the dataset has a number of missing values and must be treated accordingly before fitting any model. You can refer to this article for a primer on how to deal with missing values.

sample_submission.csv


Column Name	Description
enrollee_id

Unique ID for enrollee


target


probability of an enrollee looking for a job change
