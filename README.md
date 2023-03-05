# How I create a PowerBI report for finacial performance steering

![intro](https://github.com/minhtrang4078/How-I-create-a-PowerBI-report/blob/main/Images/intro.jpg)

# Quick look at the report
![intro2](https://github.com/minhtrang4078/How-I-create-a-PowerBI-report/blob/main/Images/preview.jpg)

[Download the *.pbix file here](https://drive.google.com/file/d/1yqmVYuUfAr-6bIJPn0E_o3ru7i-TwBZR/view?usp=sharing) 

[Download the *.pdf file here](https://github.com/minhtrang4078/How-I-create-a-PowerBI-report/blob/main/Sales%20and%20return%20report%20data.pdf)
## Context & purposes:
- This file is mainly a part of my CV, with the purpose to show how I have been working with Power BI so far.
- To keep a report/dashboard visited by users, it is very important to consider many factors besides the technical aspect of Power BI.
- The data is the combinatio of many resources and with fictional/ randomly generated for visualization purposes only, nothing related to the companies that I used to work for.
## Contents

  - [Quick summary in video](#Quick-summary-in-video)
  - [Why there can be a low Power Bi adoption (less users) through time? ](#Why-there-can-be-a-low-Power-Bi-adoption-(less-users)-through-time?)
  - [Process to create an efficient Power BI report](#Process-to-create-an-efficient-Power-BI-report)
    - Step 1: Understanding a report's purposes
    - Step 2: Data Understanding and Preparation
    - Step 3: Build the report]
    - Step 4: Final products and getting feedback
 
## Quick summary in video

? video link

## Why there can be a low Power Bi adoption (less users) through time? 
Here are some reasons that I observed:
- Firsly, THE MOST IMPORTANT REASONS
   - Insights are not useful for  business actions 
   - Insights are not actionable enough for the audiences
   - Don’t trust the results/insights (black box problem)  
- VISUALIZYTION
  - Too complicated to interpret, only serve the purpose of a small group
  - Too much details, redundant things that people don’t expect, or too simple
- DATABASE
  -  Not updated in time, slow
  -  Not enough data, or the data is unreliable
  -  Lack of data maintenance
- AUDIENCES
  - Conservative, not ready to change (e.g prefer Excel)
  - Lack of data culture within a department
  

## Process to create an efficient Power BI report
In general here is what I do:
### Step 1: Understanding a report's purposes
- Firstly, understand the audience demand: Features combined into a report based on our audience. Operational and analytical audiences may required different demands. 
- Next, understand the business problem: for example, which is the key KPI that should be included? 

### Step 2: Data Understanding and Preparation
- Follow the ELT process, and handle the data in Power Pivot with DAX language.
- Which data is possible and which data should be collected additionally?
- This is the technical part, please check the *.pbix file

### Step 3: Build the report
#### Consider features included in the report
All of the features added are based on the users' opinions. In this report, I use:
- Drill Mode: Drill up and Drill through 
- Tooltip 
- What If Analysis

#### Consider the types of visualization
- line charts, bar charts which can be shown as tables
- decomposition tree to understand key metrics

### Step 4: Final products and getting feedback
- Modify the reports based on the feedbacks for the report, and this step is like a mantainance activities for a longer time after the report creation.
- Training: how to use the reports, which answers can be found, show how the analysis is done to avoid the mistakes for someone who is skeptical about how the figures are calculated
- Track the metrics of users
