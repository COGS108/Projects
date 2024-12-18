
# COGS 108 - Final Project

**Table of Contents**

- [Project Overview](#Project-Overview)
  * [Taboo Topics](#Taboo-Topics)
- [Project Components](#Project-Components)
  * [Previous Project Review](#Previous-Project-Review)
  * [Project Proposal](#Project-Proposal)
  * [Checkpoints](#Checkpoints)
  * [Final Project](#Final-Project)
  * [Team Evaluation](#Team-Evaluation)
- [Advice](#Advice)
- [Previous COGS 108 Final Projects](#Previous-COGS-108-Final-Projects) 
- [How to Find Datasets](#How-to-Find-Datasets)

<!-- toc -->

## Project Overview 

The COGS 108 Final Project will give you the chance to explore a topic of your choice and to expand your analytical skills. By working with real data of your choosing you can examine questions of particular interest to you. 

The broad objectives for the project are to: 

* Identify the problems and goals of a real situation and dataset. 
* Choose an appropriate approach for formalizing and testing the problems and goals, and be able to articulate the reasoning for that selection. 
* Implement your analysis choices on the dataset. 
* Interpret the results of the analyses. 
* Contextualize those results within a greater scientific and social context, acknowledging and addressing any potential issues related to privacy and ethics. 
* Effectively communicate your process and findings in written (report) and oral (recorded pressentation) formats.
* Work effectively to manage a project as part of a team. 

To accomplish this you will work in teams of 4 to 5 students to conceive of and carry out an analysis project. You will find in your future careers the need to work on projects in groups frequently. 

The basic project steps (broken down in more detail below): 

* Decide on a data science question/topic you and your group mates are really interested in learning more about.
* **Proposal** Formulate a question and submit a proposal based on this idea, including background research on the topic summarizing what's already been done, a description of the *ideal* (meaning, assuming unlimited resources and access to people/data) dataset would be and ethical considerations
* Each group will receive specific feedback on their proposal and incorporate that into their first checkpoint
* **Checkpoint #1**: Groups will identify datasets that can be used to answer either their proposed question OR a new question based on project feedback and/or data availability.
* **Checkpoint #2**: Carry out EDA on proposed datasets
* **Final Report & Video**: 
  * Apply the techniques outlined and come up with a result for the dataset(s) that you've chosen to work with.
  * Assemble a Jupyter notebook that effectively communicates your entire process. Submit this as your final project report.
  * Present main findings from your project in a short video. Submit this as your final project video.
  * Submit feedback about group and individual group members. This is done individually. 

We strongly encourage you to discuss potential project ideas with your TAs and IAs, and/or with the Professor. This will give us a chance to make sure you’re on the right track even before you submit your proposal. 


### Taboo topics

While you are *encouraged* to pick a topic that helps our understanding of the world/society, you are free to pick *almost any* topic for your final project. That said, there are a few off-limit (or "taboo") topics. These topics are off-limits for three reasons: (1) these projects have been done a whole bunch of times on Kaggle already, which (2) limits the amount you can learn, and (3) makes these projects super boring to read and grade. We encourage you to pick a topic you care about, not one that is the easiest to find on the Internet. 

The taboo topics in COGS 108 are:

- movie recommendation system
- youtube video comments / trending analysis
- Kickstarter success prediction/analysis
- prediction of what makes a song popular on Spotify
- analysis that singles out a particular individual 
- AirBnb prediction

The following datasets from kaggle are also off limits as your main dataset*:

  - [Trending Youtube Video Statistics](https://www.kaggle.com/datasnaek/youtube-new)
  - [120 Years of Olympic history: athletes and results](https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results)
  - [Spotify Song Attributes](https://www.kaggle.com/geomack/spotifyclassification)
  - [Wine Reviews](https://www.kaggle.com/zynicide/wine-reviews)
  - [Yelp Dataset](https://www.kaggle.com/yelp-dataset/yelp-dataset)
  - [Student Alcohol Consumption](https://www.kaggle.com/uciml/student-alcohol-consumption)

\*If you think you have a novel idea and *really, really* want to work on one of these topics/datasets, then please reach out to the instruction team and we will let you know if your idea will work.

In addition, if a dataset is on the first few pages of Kaggle's dataset list (when sorted for either hotness or number of votes) then try to find something else.

If you think you have a novel idea and *really, really* want to work on one of these topics/datasets, then please reach out to the instruction team and we will let you know if your idea will work.
  
If you use any of these to *support* your main analysis, that is fine. But, it cannot be your main source of information.

## Project Components 

### Group Project Survey

Each group will submit one Google Form Survey indicating who is in their group. Individuals not included in groups submitted will be assigned into groups.

### Previous Project Review

Each group will submit one Google Form Survey reviewing a project from a previous quarter. This will give you a sense of what we're expecting from the project and will give you all a chance to determine what components make for a strong project and where you would have improved the project, so that you can implement these improvements in your project.

You will be assigned a project from a previous iteration of the course to review as a group.

### Project Proposal 

The Project Proposal is completed as a group. Your proposal must include the following sections:

**NAMES**: Be sure to include each member’s name

* Names : Replace the lines to list each person’s full name. Add lines as needed for your group size, and make sure each name is listed on a separate line. 

**RESEARCH QUESTION**: What is your research question? Include the specific question you're setting out to answer. This question should be specific, answerable with data, and clear. A general question with specific subquestions is permitted. (1-2 sentences)

**BACKGROUND & PRIOR WORK**: This section will present the background and context of your topic and question in a few paragraphs. Include a general introduction to your topic and then describe what information you currently know about the topic after doing your initial research. Include references to other projects who have asked similar questions or approached similar problems. Explain what others have learned in their projects.

Find some relevant prior work, and reference those sources, summarizing what each did and what they learned. Even if you think you have a totally novel question, find the most similar prior work that you can and discuss how it relates to your project. 

References can be research publications, but they need not be. Blogs, GitHub repositories, company websites, etc., are all viable references if they are relevant to your project. It must be clear which information comes from which references. (2-3 paragraphs, including at least 2 references)

**HYPOTHESIS**: What is your main hypothesis/predictions about what the answer to your question is? Briefly explain your thinking. (2-3 sentences)

**DATA**: Here, you are to *think* about and *describe* the *ideal* dataset (or datasets) you you would need to answer this question:

* What variables would you have/measure? 
* On whom/what would they be measured/collected?
* Is there a specific time period that's important? If yes, describe what the time period is and why.
* etc.

Note: For the project proposal, you do NOT have to find the actual dataset(s) needed for your project. We want you to consider what dataset you would *really* want to answer this question *perfectly*, even if such data do not exist. For the first checkpoint and onward, you will find and work with available data.

**ETHICS & PRIVACY**: Acknowledge and address any ethics & privacy related issues of your question(s), proposed dataset(s), and/or analyses. Use the information provided in lecture to guide your group discussion and thinking. If you need further guidance, check out [Deon's Ethics Checklist](http://deon.drivendata.org/#data-science-ethics-checklist). In particular:

* Are there any biases/privacy/terms of use issues with the data you propsed?
* Are there potential biases in your dataset(s), in terms of who it composes, and how it was collected, that may be problematic in terms of it allowing for equitable analysis? (For example, does your data exclude particular populations, or is it likely to reflect particular human biases in a way that could be a problem?) 
* How will you set out to detect these specific biases before, during, and after/when communicating your analysis? 
* Are there any other issues related to your topic area, data, and/or analyses that are potentially problematic in terms of data privacy and equitable impact?
* How will you handle issues you identified?

(1-2 paragraphs)


**TEAM EXPECTATIONS**: Read over the [COGS108 Team Policies](https://github.com/COGS108/Projects/blob/master/COGS108_TeamPolicies.md) individually. Then, include your group’s expectations of one another for successful completion of your COGS108 project below. Discuss and agree on what all of your expectations are. Discuss how your team will communicate throughout the quarter and consider how you will communicate respectfully should conflicts arise. By including each member’s name above and by adding their name to the  submission, you are indicating that you have read the COGS108 Team Policies, accept your team’s expectations below, and have every intention to fulfill them. These expectations are for your team’s use and benefit — they won’t be graded for their details.

**PROJECT TIMELINE PROPOSAL**: Specify your team's specific project timeline. An example timeline has been provided. Changes the dates, times, names, and details to fit your group's plan.

If you think you will need any special resources or training outside what we have covered in COGS 108 to solve your problem, then your proposal should state these clearly. For example, if you have selected a problem that involves implementing multiple neural networks, please state this so we can make sure you know what you’re doing and so we can point you to resources you will need to implement your project. Note that you are not required to use outside methods. 

To reemphasize: for the Project Proposal you are not expected to have already done any analyses for the proposed project, but what you submit should be a plan for what you will answer and what data you would ideally have for the project. (Of course, for the final project you will need to actually find the data and do the analyses.) 

#### Project Proposal - Style Guidelines 

The proposal should be written clearly and at a level understandable by a typical undergraduate student.

This is a short but detailed proposal meant to give us time to assess and critique your Final Project idea (further described below), in order to give you time to improve upon it throughout the quarter. 

You will receive feedback on your project proposal, and you are fully expected to make the changes suggested by the Professor, TAs, IAs, and your classmates on this assignment. 

Remember to proofread your Project Proposal. Do not use overly flowery and/or vague language. 

### Checkpoints 

Once you’ve settled on a problem and approach, it's time to actually find and analyze the data! 

Note: It is very important that you get right to work on the problem and don’t procrastinate. This is not a homework set — this is a large, complex problem that will take concerted effort to complete.  

#### Checkpoint #1: Data 

Your first checkpoint must include the following sections (Note that these *can* be the same as in your proposal; however, if you've made any changes/edits/incorporated feedback, you should update them): 

**NAMES**: Same as proposal.

**RESEARCH QUESTION**: See proposal specifications.

**DATASET(S)**: What data will you use to answer your question? Describe the dataset(s) in terms of number of observations, what kind of features it contains, etc. (Typically students have datasets of ~1000 observations across their datasets. This is not a requirement, but is good to know around the scale of data we're expecting.)  You are welcome (and in fact recommended) to find multiple datasets! If you do so, describe each one, and briefly explain how you will combine them together. Include the source of the dataset in the description here.

**SETUP**: Include packages used for analysis in cell provided

**DATA CLEANING**: Get each of your datasets into a usable (likely, tidy) format. Briefly explain what steps you had to take before you were able to use the datasets you chose to answer your question of interest.

* How 'clean' is the data? 
* What did you have to do to get the data into a usable format? (If you did nothing, how did you determine there was nothing to do?)
* What pre-processing steps that were required for your methods (for example, checking data distributions and performing any transformations that may be required)

#### Checkpoint #2: EDA

Your second checkpoint must include the following sections (Note that these *can* be the same as in your proposal/checkpoint #1; however, if you've made any changes/edits/incorporated feedback, you should update them): 

**NAMES**: Same as proposal.

**RESEARCH QUESTION**: See proposal specifications.

**SETUP**: See Checkpoint #1.

**DATA CLEANING**: See Checkpoint #1.

**DATA ANALYSIS & RESULTS**: This section should include markdown text and code walking us through the following:
* EDA
  * What distributions do your variables take?
  * Are there any outliers? 
  * Relationship between variables?
  
At the end of this checkpoint, it should be clear that you know your data well. Note that visualizations do not have to be perfect (yet!), but they do have to be appropriate and interpreted. Include explanations of what you learn from each visualization generated.

### Final Project 

Time to put it all together! The main products of the final project are 1) a report submitted as single Jupyter Notebook on GitHub and 2) a 3-5 minute video communicating your group project. 

#### Final Report 

You will be graded on the one group notebook submitted on GitHub in your group's project repo (which will be created for you). **The name of the file should include your group's group number. (For example, if you were in group 001, your file would be named 'FinalProject_group001.ipynb'.)**

This single notebook should include all the code you used for all components of the project (cleaning, visualization, analysis). Because we won’t be running the code in your notebook, it is important to make sure your notebook as submitted to GitHub has the code evaluated and outputs present (e.g., plots) so that we can read the project as is.

Submission must be successfully completed by Wednesday of Finals week, and should be self-contained, so that we can evaluate your entire project from the notebook alone. Additionally, each individual group member must complete the team and individual feedback survey.

These notebooks will optionally be opened to the general public, so others may read what you’ve done! You will have the option to opt out of making your project public. 

#### Report Sections - Instructions

Each of the following sections corresponds to a section in the file FinalProject_groupXXX.ipynb (template is in your group's GitHub repo). 

For sections included in your proposal and previous checkpoints, you can copy and paste into your final project, but be sure to edit these sections with feedback you received on your proposal or additional information you learned throughout the project. This report should read clearly from start to finish, explaining what you did, why you did it, and what you learned. This should be a concise and well-written report.

**PERMISSIONS**: Specify whether you want your group project to be made publicly available. Place an X in the square brackets where appropriate.

**ABSTRACT**: Include a few sentences to a few paragraphs summarizing your group’s project and results.

**NAMES**: See proposal specifications.

**RESEARCH QUESTION**: See proposal specifications.

**BACKGROUND & PRIOR WORK**: See proposal specifications.

**HYPOTHESIS**: See proposal specifications.

**DATASET(S)**: Same as Checkpoint #1.

**SETUP**: See Checkpoint #1.

**DATA CLEANING**: See  Checkpoint #1.

**DATA ANALYSIS & RESULTS**: This section should include markdown text and code walking us through the following:

* EDA (Same as Checkpoint #2, but clean visualizations up and feel free to remove unecessary visualizations)
  * What distributions do your variables take?
  * Are there any outliers? 
  * Relationship between variables?

* Analysis (Note that you will likely have to do some Googling for analytical approaches not discussed in class. This is expected for this project and an important skill for a data scientist to master.)
  * What approaches did you use? Why?
  * What were the results?
  * What were your interpretation of these findings.

* Data Visualization - There must be at least three (3) appropriate data visualizations throughout these sections. Each visualization must included an interpretation of what is displayed *and* what should be learned from that visualization. Be sure that the appropriate type of visualization is generated given the data that you have, axes are all labeled, and the visualizations clearly communicate the point you’re trying to make.

**ETHICS & PRIVACY**: See proposal specifications. (be sure to update with what you actually did to take the ethical considerations into account for the analysis you did!)

**CONCLUSION & DISCUSSION**: Discuss your project. Summarize your data and question. Briefly describe your analysis. Summarize your results and conclusions. Be sure to mention any limitations of your project. Discuss the impact of this work on society. (~2-3 paragraphs)


#### Video

Each group will submit a single 3-5 minute video on canvas communicating their group's final project. Only one member of each group will submit the video on Canvas, but the grade received will apply to everyone. This video will have to incorporate the visualization and effective communication strategies discussed in class. However, this can be creative. It is up to the group to decide how to most effectively communicate their project and results. 

All group members must participate in the completion of the video submitted; however, not everyone has to be on screen or talk in the video. How you delegate tasks here is up to the group. 

#### Grading 

**Checkpoints*

Checkpoints will be graded using a very broad rubric. Each rubric item will be graded Exceptional (E), Proficient (P), Developing (D), or Unsatisfactory (U). Full points will be earned for any item that earns E or P. Staff will work to heavily comment so that you know what to fix going forward.

Groups will have the ability to earn back points lost on the previous checkpoint during the grading of the subsequent checkpoint. For example, points lost on the proposal can be earned back on the first checkpoint. However, points lost on the proposal that remain a deduction on the first checkpoint, can no longer be earned back on the second checkpoint.

To indicate to your grader what you have addressed in each submission from the prior psubmission, add a comment to the issue where points were initially lost explaining your changes.

For this process to work, **all grading issues on GitHub must remain open** . Please do not close them.

**Final Report**

Your final project report and video will be graded based on the rubric below. For the report, make sure you address each rubric section in the notebook, in an organized manner, using Markdown cells for textual descriptions. Note that you *can* add subsections or change up the organization, if your project would be clearer with you doing so.

The grading rubric for the Final Project is as follows: 

| Category  | Percentage of Project Grade | 
|---|---|
| Abstract, Question, & Background | 10 |
| Data Description | 5 |
| Data Cleaning/Processing | 5 |
| Data Visualization | 15 |
| Data Analysis & Results | 25 |
| Ethics & Privacy | 10 |
| Conclusion & Discussion | 10 |
| Written Communication | 10   | 
| Oral Communication (video) |  10 | 

**Note**: Individual grades can be adjusted based on the feedback provided in individual surveys submitted. This means that team members in the same group can receive different scores from one another, if evaluations suggest that contributions were not evenly distributed. To avoid this, work together as a group and ensure that you’re contributing to the project.

### Team Evaluation

Each individual will submit a short survey providing feedback about their experience with the COGS 108 project and working with their team.  The professor will be the only person to see this feedback and will use this information when deciding individual grades. 

### Timeline 

To make sure we are all progressing well toward the end of the project, we are implementing checkpoints this quarter and requiring that your proposal includes a detailed timeline of dates/times for meetings that work for your group.

## Final Project Checklist

Students often ask for a rubric. You can use this checklist to help guide your thinking on the final project. If you check off all the boxes below, you should be in good shape to get a perfect score on your final project.

### Abstract, Question & Background

**Abstract**:
- [ ] Write a clear summary of what you did
- [ ] Briefly describe the results of your project 
- [ ] Limit overview to ~1 paragraph

**Research Question**:
- [ ] Include a specific, clear data science question
- [ ] Make sure what you're measuring (variables) to answer the question is clear

**Background & Prior Work**:
- [ ] Include a general introduction to your topic
- [ ] Include explanation of what work has been done previously
- [ ] Include citations or links to previous work

**Hypothesis**:
- [ ] Include your team's hypothesis
- [ ] Ensure that this hypothesis is clear to readers
- [ ] Explain why you think this will be the outcome (what was your thinking?)

### Dataset(s):
- [ ] Include an explanation of dataset(s) used (i.e. features/variables included, number of observations, information in dataset)
- [ ] Source included (if outside dataset(s) being used)

### Data Analysis:

**Data Cleaning & Pre-processing**
- [ ] Perform Data Cleaning and explain steps taken OR include an explanation as to why data cleaning was unnecessary (how did you determine your dataset was ready to go?)
- [ ] Dataset actually clean and usable after data wrangling steps carried out

**Data Visualization**:
- [ ] Include at least three visualizations
- [ ] Clearly label all axes on plots
- [ ] Type of all plots appropriate given data displayed
- [ ] Interpretation of each visualization included in the text

**Data Analysis & Results**:
- [ ] EDA carried out with explanations of what was done and interpretations of output included
- [ ] Appropriate analysis performed 
- [ ] Output of analysis interpreted and interpretation included in notebook

### Privacy/Ethics Considerations:
- [ ] Thoughtful discussion of ethical concerns included
- [ ] Ethical concerns consider the whole data science process (question asked, data collected, data being used, the bias in data, analysis, post-analysis, etc.)
- [ ] How your group handled bias/ethical concerns clearly described

### Conclusion & Discussion:
- [ ] Clear conclusion (answer to the question being asked) and discussion of results
- [ ] Limitations of analysis discussed
- [ ] Does not ramble on beyond providing necessary information

### Video:
- [ ] Question asked is clear to listeners
- [ ] Effective visualizations presented
- [ ] Clear explanations throughout
- [ ] Take home message clear
- [ ] Within 3-5 min time limit

### Final Checks:
- [ ] Edit all text for clarity
- [ ] Remove all instructions
- [ ] Be sure text included throughout to guide reader
- [ ] Check to make sure all text and images are visible
- [ ] Names included
- [ ] Renamed file : `FinalProject_groupXXX-Fa22.ipynb`, where 'XXX' is replaced by your group's group number

### After the course is done:
- If you checked YES to make project public: the final project notebook (and only that!) will be placed in a repo with the rest of this quarters public reports. This helps future students by providing examples!
- Your project repo will remain available to you in the near future. We cannot guarentee that will always be the case. That repo will never be public.
- If you would like your own copy of the entire repo you should follow these instructions: https://docs.github.com/en/repositories/creating-and-managing-repositories/duplicating-a-repository Once you have done that it is yours forever. You will also be able to control access to the mirror (make it public or private as you would prefer) 


## Advice 

The main pieces of advice are: 

* Start early 
* Work consistently 
* Be a good teammate 
* Work as a team 
* Seek advice when you are unsure, and see it early and often! 
* Talk to your TAs, IAs, and professor - we’re here to help! 
* Choose a general interest domain and question of interest, and then choose a dataset, not vice versa. I promise it will go much better. 
* Start early!!!!! 

As far as resources go, it is okay to ask other teams what they are doing in terms of sources, presentation plans, and so on. As long as you are not using another team’s work and claiming it as your own, collaboration with classmates is encouraged. If you find a good source of datasets, please share with everyone on Piazza! 

## Previous COGS 108 Final Projects 

See Prof. Voytek’s write-up of excellent class projects from the Spring 2017 instance of COGS 108 [here](https://voyteklab.com/uc-san-diego-data-science-projects/), all of which received perfect scores. 

Additionally, previous projects can be viewed from when this course ran in [Spring 2017](https://github.com/COGS108/FinalProjects-Sp17), [Winter 2018](https://github.com/COGS108/FinalProjects-Wi18), [Spring 2019](https://github.com/COGS108/FinalProjects-Sp19), [Fall 2019](https://github.com/COGS108/FinalProjects-Fa19), [Winter 2020](https://github.com/COGS108/FinalProjects-Wi20), [Spring 2020](https://github.com/COGS108/FinalProjects-Sp20), [Fall 2020](https://github.com/COGS108/FinalProjects-Fa20),  [Winter 2021](https://github.com/COGS108/FinalProjects-Wi21), [Spring 2023](https://github.com/COGS108/FinalProjects-Sp23). Note first, that these projects are of variable quality and second, that if you get inspiration or code from previous projects, this must be noted in your project, giving attribution to the former groups’ work.

## How to Find Datasets 

The purpose of this project is to find a real-world problem and dataset (or likely, datasets!) that can be analyzed with the techniques learned in class and those you learn on your own. It is imperative that by doing so you believe extra information will be gained — that you believe you can discover something new!

You must use at least one dataset containing at least approximately 1000 observations (if your data are smaller but you feel they are sufficient, chat with the professor). You are welcome (and in fact recommended) to find multiple datasets! 

The best datasets are the ones that can help you answer your question of interest. 

Your question could be just for fun: Using text mining of song lyric websites to identify the most commonly used phrases and sentiments by decade. 

Your question could be scientific: Scrape data from animal taxonomies and Wikipedia to figure out if larger animals are more likely to be carnivores?. 

Or, ideally, your question can be aimed at civic or social good, for example, use mapping, transit, and car accident data to identify which parts of San Diego are most in need of dedicated bike lanes. 

To help you find datasets, we have collected a list of websites that have a considerable number of open source data sets and included them at the end of this document.. 

Eventually you will all have to decide on a problem to tackle, with each member of the team having a clear, delineated role in the project. 

### Dataset Resource List 

Here, is a list of potential locations to find datasets and problems to investigate. If you have another dataset or search location, that is great! 

* [Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets/blob/master/README.rst)
* [Data.gov](https://catalog.data.gov/dataset)
* [Data Is Plural](https://docs.google.com/spreadsheets/d/1wZhPLMCHKJvwOkP4juclhjFgqIY8fQFMemwKL2c64vk/edit#gid=0)
* [UCSD Datasets](https://ucsd.libguides.com/data-statistics/home)
* [Datasets | Deep Learning](http://deeplearning.net/datasets/)
* [Stanford | Social Science Data Collection](https://data.stanford.edu/)
* [Eviction Lab (email required)](https://evictionlab.org/get-the-data/)
* [San Diego Data](https://data.sandiego.gov/)
* [US Census](https://www.census.gov/)
* [Open Climate Data](http://openclimatedata.net/)
* [Data and Story Library](https://dasl.datadescription.com/datafiles/)
* [UCSD behavioral mobile data](http://extrasensory.ucsd.edu/)
* [Kaggle](https://www.kaggle.com/)
* [FiveThirtyEight](https://data.fivethirtyeight.com/)
* [data.world](https://data.world/)
* [Free Datasets - R and Data Mining ](http://www.rdatamining.com/resources/data)
* [Data Sources for Cool Data Science Projects](https://blog.thedataincubator.com/2014/10/data-sources-for-cool-data-science-projects-part-1/)


