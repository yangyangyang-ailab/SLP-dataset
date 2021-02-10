# SLP-dataset

## Introduction

SLP dataset is a valuable dataset from K-12 education. It mainly has two properties:

**——Multi-Dimensional**: It covers the data from five different dimensions, namely student demographic information, psychometric intelligence information, academic performance information, family information and school information;

**——Consecutive**: It automatically captures the learner's academic performance data during their three-year study (mainly from 7th grade to 9th grade) on 8 different subjects, namely Math, Physics, Chemistry, Biology, History, Chinese, Geography and English.

## Dataset Description

The SLP dataset is available in the form of multiple CSV files (each value is separated by comma, and the first line in each table shows the column name). Tables can be easily linked using the unique identifier *student_id*, while only the *Table schoolInfo* uses the *school_id* as its unique identifier.

### Academic Performance Information
The two zip files, named **termtestRecord** and **unittestRecord**, contain multiple tables with the identical table structure, which provide the student academic performance information in term test and unit test respectively. 

In each zip file, each sub-table contains individuals' subject score information. For example, the sub-table *termtestRecord-BIO* inside **termtestRecord** stores the term test results of Biology, which currently consists of 500,562 rows.

### Psychometric Test Information
*Table psychomericRecord* contains the student's psychometric intelligence score, and it consists of 1161 rows. Note the SLP dataset only includes participants who agreed to take and share their psychometric test results.

### Family Information
*Table familyInfo* contains student's family information, including parents' age, education background, employment information, financial status and family intimacy (e.g., how often the student meets with father or mother). The table consists of 3189 rows, and only includes the students who fully completed the family information portion in the online survey and confirmed the truth of it.

### School Information
*Table schoolInfo* contains the school's demographic information, including the school type, location information and teacher's education background. It consists of 32 rows, and for teachers' education background, 3 school's data are missing (marked as n.a. in the table).

### Student Demographic Information
*Table studentInfo* contains the basic demographic information of students, including their gender, school and class ID. The table consists of 4830 rows, and all the school and class information are anonymized.

## Applications
With a 3-year consecutive data collecting process among a large-scale of learners, this dataset would provide valuable information and foster the cross-disciplinary research for learning analytics on a broader canvas. We welcome researchers to use our dataset only for research purpose. **Please make sure you state the source of the data when using them for paper publication.**
