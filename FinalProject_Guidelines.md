
# COGS 108 - Final Project

Everything you need to know about the COGS 108 group project: what you'll submit, when, what each submission must include, and how it's graded.

> **Tip:** On GitHub, click the list icon (☰) at the top right of this file for a clickable outline of every section.

## Contents

- [Project Overview](#project-overview)
  - [At a Glance](#at-a-glance)
- [Ground Rules](#ground-rules)
  - [Taboo Topics](#taboo-topics)
  - [Data Requirements](#data-requirements)
  - [AI and Outside Help Policy](#ai-and-outside-help-policy)
- [Your Group Repo](#your-group-repo)
- [Project Components](#project-components)
  - [Group Project Survey](#group-project-survey)
  - [Previous Project Review](#previous-project-review)
  - [Project Proposal](#project-proposal)
  - [Checkpoint #1: Data](#checkpoint-1-data)
  - [Checkpoint #2: EDA](#checkpoint-2-eda)
  - [Oral Exam](#oral-exam)
  - [Final Report](#final-report)
  - [Video](#video)
  - [Team Evaluation](#team-evaluation)
- [Section Requirements](#section-requirements) — what goes in each notebook section, and which submissions need it
- [Grading](#grading)
  - [Weights](#weights)
  - [How Rubrics Are Scored](#how-rubrics-are-scored)
  - [Earning Points Back](#earning-points-back)
- [Final Project Checklist](#final-project-checklist)
- [After the Course](#after-the-course)
- [Resources](#resources)
  - [Advice](#advice)
  - [Previous COGS 108 Final Projects](#previous-cogs-108-final-projects)
  - [How to Find Datasets](#how-to-find-datasets)

---

## Project Overview

The COGS 108 Final Project will give you the chance to explore a topic of your choice and to expand your analytical skills. By working with real data of your choosing you can examine questions of particular interest to you.

The broad objectives for the project are to:

* Identify the problems and goals of a real situation and dataset.
* Choose an appropriate approach for formalizing and testing the problems and goals, and be able to articulate the reasoning for that selection.
* Implement your analysis choices on the dataset.
* Interpret the results of the analyses.
* Contextualize those results within a greater scientific and social context, acknowledging and addressing any potential issues related to privacy and ethics.
* Effectively communicate your process and findings in written (report) and oral (recorded presentation) formats.
* Work effectively to manage a project as part of a team.

To accomplish this you will work in teams of 4 to 5 students to conceive of and carry out an analysis project. You will find in your future careers the need to work on projects in groups frequently.

We strongly encourage you to discuss potential project ideas with your TAs and IAs, and/or with the Professor. This will give us a chance to make sure you're on the right track even before you submit your proposal.

### At a Glance

| Component | What you do | Who | Submitted via | When |
|---|---|---|---|---|
| [Group Project Survey](#group-project-survey) | Tell us who is in your group | Group | Google Form | See course schedule |
| [Previous Project Review](#previous-project-review) | Review a project from a previous quarter | Group | Google Form | See course schedule |
| [Project Proposal](#project-proposal) | Pick a question; describe background, hypothesis, the *ideal* dataset and candidate real datasets, and ethical considerations | Group | `00-ProjectProposal.ipynb` in your group repo | See course schedule |
| [Checkpoint #1: Data](#checkpoint-1-data) | Obtain and wrangle your real dataset(s), updating earlier sections with feedback | Group | `01-DataCheckpoint.ipynb` in your group repo | See course schedule |
| [Checkpoint #2: EDA](#checkpoint-2-eda) | Exploratory data analysis of your dataset(s), updating earlier sections with feedback | Group | `02-EDACheckpoint.ipynb` in your group repo | See course schedule |
| [Oral Exam](#oral-exam) | Each member answers questions about the project (through the EDA checkpoint) | Group (each member answers) | In person, during lecture | Week 10 |
| [Final Report](#final-report) | Complete analysis, written up in a single Jupyter notebook | Group | `03-FinalProject.ipynb` in your group repo | Wednesday of Finals week |
| [Video](#video) | 3-5 minute video presenting your project to a non-technical audience | Group | Link in `03-FinalProject.ipynb` | With the Final Report |
| [Team Evaluation](#team-evaluation) | Feedback on your team and each member's contributions | Individual | Survey | See course schedule |

<sub>[↑ Back to contents](#contents)</sub>

---

## Ground Rules

### Taboo Topics

While you are *encouraged* to pick a topic that helps our understanding of the world/society, you are free to pick *almost any* topic for your final project. That said, there are a few off-limits (or "taboo") topics and datasets. These are off-limits for three reasons: (1) these projects have been done a whole bunch of times on Kaggle already, which (2) limits the amount you can learn, and (3) makes these projects super boring to read and grade. We encourage you to pick a topic you care about, not one that is the easiest to find on the Internet.

**Taboo topics**

- Movie recommendation systems
- YouTube video comments / trending analysis
- Kickstarter success prediction/analysis
- Prediction of what makes a song popular on Spotify
- Airbnb prediction

**Taboo datasets.** The following Kaggle datasets cannot be your *main* dataset:

- [Trending YouTube Video Statistics](https://www.kaggle.com/datasnaek/youtube-new)
- [120 Years of Olympic history: athletes and results](https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results)
- [Spotify Song Attributes](https://www.kaggle.com/geomack/spotifyclassification)
- [Wine Reviews](https://www.kaggle.com/zynicide/wine-reviews)
- [Yelp Dataset](https://www.kaggle.com/yelp-dataset/yelp-dataset)
- [Student Alcohol Consumption](https://www.kaggle.com/uciml/student-alcohol-consumption)

More generally, if a dataset is on the first few pages of Kaggle's dataset list (when sorted by either hotness or number of votes), try to find something else.

Using any of these datasets to *support* your main analysis is fine. They just cannot be your main source of information.

**Exceptions.** If you think you have a novel idea and *really, really* want to work on one of the topics or datasets above, please reach out to the instruction team and we will let you know if your idea will work.

**Not allowed, no exceptions:** any analysis that singles out a particular individual (who is not a public figure).

### Data Requirements

You must use at least one dataset containing at least approximately 1000 observations. (If your data are smaller but you feel they are sufficient, chat with the professor.) You are welcome (and in fact encouraged) to find and combine multiple datasets! See [How to Find Datasets](#how-to-find-datasets) for ideas and a list of places to look.

### AI and Outside Help Policy

You are allowed to use AI and to seek help from people outside your group. AI can be used as a collaborative tool, just like an additional group member: for brainstorming, background research, editing, debugging, formatting, and clarifying your thinking. However, **every member of your group is responsible for understanding every part of the project**, and your group is responsible for any errors or falsehoods AI introduces. (Remember that each member may be asked about any part of the project in the [Oral Exam](#oral-exam).)

Every notebook you submit ends with an [AI and Outside Help](#ai-and-outside-help) table where you record the help you received.

<sub>[↑ Back to contents](#contents)</sub>

---

## Your Group Repo

Each group gets a private GitHub repo, created for you from our template. It is visible only to your group and the course staff. You will be graded **solely on the four numbered notebooks** in this repo, and you will receive grades and feedback as GitHub Issues on the repo.

```
00-ProjectProposal.ipynb   # Project Proposal
01-DataCheckpoint.ipynb    # Checkpoint #1: Data
02-EDACheckpoint.ipynb     # Checkpoint #2: EDA
03-FinalProject.ipynb      # Final Report (and link to your video)
data/
  00-raw/                  # raw data, exactly as downloaded
  01-interim/              # optional intermediate stages of wrangling
  02-processed/            # final, fully wrangled data used for EDA and analysis
modules/
  get_data.py              # get_raw(): downloads data from URLs into data/00-raw/
results/                   # saved figures and analysis outputs
.gitignore                 # by default, keeps data files out of GitHub
```

The numbers in the notebook filenames give the order things are due. Keep these four notebooks in place with these names; beyond that, the repo is yours to organize as you see fit.

A few things to know:

- **Each notebook starts with a rubric cell.** It shows how that submission will be graded. **Delete this cell before you submit.**
- **Data stays out of GitHub by default.** GitHub has low limits on file and repo size, so the `.gitignore` is set up so that data files are not committed. Instead, the setup code cells in the checkpoint notebooks use `get_raw()` to download your data from its original source (or your own cloud storage) into `data/00-raw/`. If you want to store small data files directly in GitHub, edit `.gitignore`.
- **Data moves through `data/` in stages.** Load raw data from `data/00-raw/`, optionally save intermediate stages to `data/01-interim/`, and write your final, fully wrangled data to `data/02-processed/`. Later notebooks should load the processed data rather than re-running all of the downloading and wrangling.
- **Put reusable code in `modules/`.** Any code you call repeatedly (for example, the same pre-processing, analysis, or visualization applied to different subsets of the data) should become a function or class in a `.py` file in `modules/` that your notebooks import. See `modules/get_data.py` for an example.
- **Save long-running results in `results/`.** If a figure or analysis takes a long time to compute, save its output to `results/` and reload it in your notebook.

<sub>[↑ Back to contents](#contents)</sub>

---

## Project Components

Every notebook builds on the one before it. Each checkpoint repeats **all** of the sections from your proposal, updated with the feedback you received and anything you've learned since, and then adds new sections. See [Section Requirements](#section-requirements) for what each section should contain.

### Group Project Survey

Each group will submit one Google Form Survey indicating who is in their group. Individuals not included in groups submitted will be assigned into groups.

### Previous Project Review

Each group will submit one Google Form Survey reviewing a project from a previous quarter. You will be assigned a project from a previous iteration of the course to review as a group. This will give you a sense of what we're expecting from the project and will give you all a chance to determine what components make for a strong project and where you would have improved the project, so that you can implement these improvements in your project. (Curious about more? Browse [Previous COGS 108 Final Projects](#previous-cogs-108-final-projects).)

### Project Proposal

**Notebook:** `00-ProjectProposal.ipynb`

The Project Proposal is completed as a group. It must include the following sections:

[Authors](#authors) · [Research Question](#research-question) · [Background and Prior Work](#background-and-prior-work) · [Hypothesis](#hypothesis) · [Data](#data) · [Ethics](#ethics) · [Team Expectations](#team-expectations) · [Teammate Roles](#teammate-roles) · [Project Timeline](#project-timeline) · [AI and Outside Help](#ai-and-outside-help)

If you think you will need any special resources or training outside what we have covered in COGS 108 to solve your problem, then your proposal should state these clearly. For example, if you have selected a problem that involves implementing multiple neural networks, please state this so we can make sure you know what you're doing and so we can point you to resources you will need to implement your project. Note that you are not required to use outside methods.

To reemphasize: for the Project Proposal you are not expected to have already done any analyses for the proposed project, but what you submit should be a plan for what you will answer, what data you would ideally have, and what real data might be available. (Of course, for the final project you will need to actually obtain the data and do the analyses.)

**Style guidelines**

The proposal should be written clearly and at a level understandable by a typical undergraduate student.

This is a short but detailed proposal meant to give us time to assess and critique your Final Project idea, in order to give you time to improve upon it throughout the quarter.

You will receive feedback on your project proposal, and you are fully expected to make the changes suggested by the Professor, TAs, IAs, and your classmates on this assignment.

Remember to proofread your Project Proposal. Do not use overly flowery and/or vague language.

### Checkpoint #1: Data

**Notebook:** `01-DataCheckpoint.ipynb`

Once you've settled on a problem and approach, it's time to actually obtain and wrangle the data!

Note: It is very important that you get right to work on the problem and don't procrastinate. This is not a homework set — this is a large, complex problem that will take concerted effort to complete.

Groups will identify datasets that can be used to answer either their proposed question OR a new question based on project feedback and/or data availability. The goal of this checkpoint is to demonstrate that you can obtain and wrangle data; you can still add more datasets later if these turn out not to be sufficient.

This checkpoint includes **every proposal section** (updated to address your feedback), plus the [setup code cells](#setup-code-cells) and your real datasets and wrangling in the [Data](#data) section:

[Authors](#authors) · [Research Question](#research-question) · [Background and Prior Work](#background-and-prior-work) · [Hypothesis](#hypothesis) · [Data](#data) (with [setup code cells](#setup-code-cells)) · [Ethics](#ethics) · [Team Expectations](#team-expectations) · [Project Timeline](#project-timeline) · [AI and Outside Help](#ai-and-outside-help)

### Checkpoint #2: EDA

**Notebook:** `02-EDACheckpoint.ipynb`

This checkpoint includes everything from Checkpoint #1 (updated to address your feedback), plus your [Exploratory Data Analysis](#exploratory-data-analysis):

[Authors](#authors) · [Research Question](#research-question) · [Background and Prior Work](#background-and-prior-work) · [Hypothesis](#hypothesis) · [Data](#data) (with [setup code cells](#setup-code-cells)) · [Exploratory Data Analysis](#exploratory-data-analysis) · [Ethics](#ethics) · [Team Expectations](#team-expectations) · [Project Timeline](#project-timeline) · [AI and Outside Help](#ai-and-outside-help)

At the end of this checkpoint, it should be clear that you know your data well. Note that visualizations do not have to be perfect (yet!), but they do have to be appropriate and interpreted. Include explanations of what you learn from each visualization generated.

### Oral Exam

Each group will take an oral exam during Lecture time in week 10 as a group. Each group will sign up for a specific oral exam slot with their TA before week 10. For each oral exam, each group member will be asked to answer a few questions about their project (up to and including work in the EDA checkpoint). TAs will choose which group member will answer which question. As such, each individual group member must be familiar with the entire project.

### Final Report

**Notebook:** `03-FinalProject.ipynb`

Time to put it all together! The main products of the final project are 1) a report submitted as a single Jupyter notebook, `03-FinalProject.ipynb`, in your group repo and 2) a 3-5 minute [video](#video) communicating your group project, linked from that notebook.

Because we won't be running the code in your notebook, make sure your notebook as submitted to GitHub has the code evaluated and outputs present (e.g., plots) so that we can read the project as is. Submission must be successfully completed by Wednesday of Finals week.

**Keep it lean.** The final report should not be overly long. It should read clearly from start to finish, explaining what you did, why you did it, and what you learned.

- If your data wrangling is long and complicated, remove it from the final report and replace it with a statement like "To see the code responsible for wrangling the data, see `01-DataCheckpoint.ipynb`. From here on we simply load the processed data." Then load your data from `data/02-processed/`.
- Remove any EDA or analysis you later decided was an unnecessary side quest.
- If your EDA or analysis code is very long (in lines or in time to compute), save its figures or results to `results/` and reload them here, with a statement pointing to the notebook or `.py` file that produced them.

Your final report must include the following sections:

[Title & Permissions](#title--permissions) · [Link to Video](#link-to-video) · [Abstract](#abstract) · [Authors](#authors) · [Research Question](#research-question) · [Background and Prior Work](#background-and-prior-work) · [Hypothesis](#hypothesis) · [Data](#data) · [Exploratory Data Analysis](#exploratory-data-analysis) · [Analyses](#analyses) · [Ethics](#ethics) · [Discussion and Conclusion](#discussion-and-conclusion) · [AI and Outside Help](#ai-and-outside-help)

For sections included in your proposal and previous checkpoints, you can copy and paste into your final project, but be sure to edit these sections with feedback you received or additional information you learned throughout the project.

Final reports will optionally be made public, so others may read what you've done! See [Title & Permissions](#title--permissions) and [After the Course](#after-the-course).

### Video

Each group will create a single 3-5 minute video communicating their group's final project **to a non-technical audience**. Put a link to the video in the "Link to video" field at the top of `03-FinalProject.ipynb`. Make sure the link is viewable by anyone who has it, and test it in a private/incognito browser window before you submit. The grade received will apply to everyone in the group.

This video will have to incorporate the visualization and effective communication strategies discussed in class. However, this can be creative. It is up to the group to decide how to most effectively communicate their project and results.

All group members must participate in the completion of the video submitted; however, not everyone has to be on screen or talk in the video. How you delegate tasks here is up to the group.

### Team Evaluation

At the end of the quarter, each individual will submit a short survey providing feedback about their experience with the COGS 108 project, their team, and each group member's contributions. This is done individually, and every group member must complete it. The professor will be the only person to see this feedback.

This feedback is used when deciding individual grades: individual grades can be adjusted based on these evaluations, which means team members in the same group can receive different scores from one another if evaluations suggest that contributions were not evenly distributed. To avoid this, work together as a group and ensure that you're contributing to the project.

<sub>[↑ Back to contents](#contents)</sub>

---

## Section Requirements

Each notebook template already contains these sections, with instructions in each. This table shows which sections each submission needs; click a section name for what it should contain. Sections carried forward from an earlier submission should be **updated** to address feedback and reflect what you've learned.

| Section | Proposal | Checkpoint #1 | Checkpoint #2 | Final Report |
|---|:---:|:---:|:---:|:---:|
| [Title & Permissions](#title--permissions) | | | | ✓ |
| [Link to Video](#link-to-video) | | | | ✓ |
| [Abstract](#abstract) | | | | ✓ |
| [Authors](#authors) | ✓ | ✓ | ✓ | ✓ |
| [Research Question](#research-question) | ✓ | ✓ | ✓ | ✓ |
| [Background and Prior Work](#background-and-prior-work) | ✓ | ✓ | ✓ | ✓ |
| [Hypothesis](#hypothesis) | ✓ | ✓ | ✓ | ✓ |
| [Data](#data) | Ideal + candidate real datasets | Real datasets + wrangling | ✓ | ✓ (kept lean) |
| [Setup Code Cells](#setup-code-cells) | | ✓ | ✓ | As needed |
| [Exploratory Data Analysis](#exploratory-data-analysis) | | | ✓ | ✓ (cleaned up) |
| [Analyses](#analyses) | | | | ✓ |
| [Ethics](#ethics) | ✓ | ✓ | ✓ | ✓ |
| [Team Expectations](#team-expectations) | ✓ | ✓ | ✓ | |
| [Teammate Roles](#teammate-roles) | ✓ | | | |
| [Project Timeline](#project-timeline) | ✓ | ✓ (updated) | ✓ (updated) | |
| [Discussion and Conclusion](#discussion-and-conclusion) | | | | ✓ |
| [AI and Outside Help](#ai-and-outside-help) | ✓ | ✓ | ✓ | ✓ (whole project) |

### Title & Permissions

*Final Report.* Replace the template title with your project's title. Then place an X in the appropriate bracket to specify whether you would like your final report, including the names of the authors, to be made publicly available. Only your final report is made public; your group repo stays private.

### Link to Video

*Final Report.* Replace the placeholder with a link to your [video](#video) that anyone with the link can view.

### Abstract

*Final Report.* Write **one paragraph** giving a brief overview of why you did this project, how you did it, and your major findings and conclusions.

### Authors

*All submissions.* List each group member along with how they contributed, using the modified [CRediT taxonomy of contributions](https://credit.niso.org) provided in the template: Analysis, Background research, Conceptualization, Data curation, Experimental investigation, Methodology, Project administration, Software, Visualization, Writing – original draft, Writing – review & editing. Contributions will change over the course of the checkpoints, so update this list each time.

### Research Question

*All submissions.* Include a specific, clear data science question. It should be answerable with data and unambiguous: when we read it, we should know clearly what your project will be about. Make sure it is clear which metrics/variables you need to answer the question, and that the question suggests what kind of analysis is appropriate (for example, a prediction task or a statistical inference task). A general question with specific subquestions is permitted, and bullet points are fine. (No more than 5-6 sentences.)

### Background and Prior Work

*All submissions.* Present the background and context of your topic and question. Include a general introduction to your topic and then describe what information you currently know about the topic after doing your initial research. Include references to other projects who have asked similar questions or approached similar problems, and explain what others have learned.

Find relevant prior work, and reference those sources, summarizing what each did and what they learned. Even if you think you have a totally novel question, find the most similar prior work that you can and discuss how it relates to your project. Useful sources include fundamental work in the broad field (think textbook chapters or famous case studies), very similar projects, and primary research or review articles about techniques you will use or obstacles you will face. Review papers can be especially helpful. References can be research publications, but they need not be: blogs, GitHub repositories, company websites, and reputable news or magazine articles are all viable if they are relevant. When two possible citations exist, choose the one that seems more central to the field.

Use inline citations (the template shows how to do this with footnotes) so it is clear which information comes from which reference. Don't make a bunch of claims without citation and then put a bibliography at the end.

**Be aware that AI sometimes invents citations**, and it does not reliably pick out the most important sources. Verify every citation yourself.

(3-6 paragraphs, with a *minimum* of 3 relevant citations)

### Hypothesis

*All submissions.* Your hypothesis is different from your question: it is what you think the answer to your question will be. For example, if your question is "What is the association between X and Y?", your hypothesis might be that there is a strong correlation between X and Y, or no correlation, or some other relationship. Make sure it is clear to readers, and briefly explain why you think this will be the outcome, referring to your background section as needed. (2-3 sentences)

### Data

*All submissions.* What this section contains changes as your project progresses.

**Proposal:**

1. Describe the **ideal** dataset you would want to answer your question, even if such data do not exist:
   1. What variables?
   2. How many observations are needed?
   3. Who/what/how would these data be collected?
   4. How would these data be stored/organized?
2. Search for potential **real** datasets that could be useful for this project. For each one, write 3-5 sentences describing:
   1. where the data is located (e.g., URL) and anything you need to do to use it (e.g., ask for permission, fill out an application)
   2. the important variables in this dataset that you might use

**Checkpoint #1 onward:**

Start with a **data overview** describing each real dataset you are using:

- Dataset name
- Link to the dataset
- Number of observations
- Number of variables
- Description of the variables most relevant to this project
- Any shortcomings this dataset has with respect to the project

If you use multiple datasets, add a few sentences about how you plan to combine them.

Then give **each dataset its own section** (with a descriptive title, not "Dataset #1"). In the text, describe the important metrics, what units they are in, and what they mean, along with any major concerns with the dataset (for example, a self-selected sample). In the code:

1. load the dataset from `data/00-raw/`
2. make the dataset tidy, or demonstrate that it was already tidy
3. demonstrate the size of the dataset
4. find out how much data is missing, where it's missing, and whether it's missing at random or seems to have any systematic relationships in its missingness
5. find and flag any outliers or suspicious entries
6. clean the data, or demonstrate that it was already clean, and justify your choices (for example, how you dealt with missingness)
7. write the final, fully wrangled version of your data to `data/02-processed/` (and, optionally, intermediate stages to `data/01-interim/`)

If you have multiple datasets, add a final section demonstrating how you join, align, or cross-reference them.

**Final Report:** keep this section lean; see [Final Report](#final-report).

### Setup Code Cells

*Checkpoints #1 and #2, and the Final Report as needed.* The checkpoint templates include two setup code cells at the start of the Data section:

- An **autoreload** cell. Run it whenever you are actively developing modules in `.py` files, so that changes to your modules are picked up by the notebook.
- A **data download** cell. Replace the example URLs and filenames with your actual data sources; it uses `get_raw()` from `modules/get_data.py` to download each file into `data/00-raw/`. You only need to run it once after cloning the repo (and again if the data change).

See [Your Group Repo](#your-group-repo) for how the `data/` and `modules/` folders are organized.

### Exploratory Data Analysis

*Checkpoint #2 and Final Report.* Explicitly load the fully wrangled data you will use from `data/02-processed/`, rather than forcing readers to re-run the data-getting and wrangling cells. Then carry out the EDA your project needs, with each part in its own clearly titled subsection. Interleave the code that generates each result with properly annotated figures and with text that describes what you did, why, and how to interpret it. Consider:

* What distributions do your variables take?
* Are there any outliers?
* What are the relationships between variables?

Any code you run repeatedly should be turned into a function or class in `modules/` (see [Your Group Repo](#your-group-repo)).

For the Final Report, clean your EDA up: keep what supports your question and remove side quests.

### Analyses

*Final Report.* Present the analyses you did beyond EDA, each in its own clearly titled subsection, interleaving code, properly annotated figures, and text that puts the results into context. Examples include inferential statistics where you calculate p-values (like a t-test or a Monte Carlo simulation), regression models, or machine learning models. You will likely have to do some Googling for analytical approaches not discussed in class; this is expected for this project and an important skill for a data scientist to master.

* What approaches did you use? Why?
* What were the results?
* What is your interpretation of these findings?

To meet the bar for proficient on the rubric, include **at least two analyses beyond EDA**: for example, two different techniques (inference vs. machine learning, or a t-test vs. regression), the entire dataset vs. a stratified version, or two different proxies for the same concept. Each analysis should address the question/hypothesis and be technically appropriate.

**Data visualization:** your report needs at least three (3) relevant, appropriate visualizations. Each should be the right type of plot for your data, with legible labels, axes, legends, and titles, and each must be referenced and interpreted in the text: what is displayed *and* what should be learned from it.

### Ethics

*All submissions.* The template includes the [Deon data science ethics checklist](https://deon.drivendata.org/). Keep the checklist in your notebook, and for each item:

- put an X in the box once you have considered the item
- **if the item is relevant** to your project, add a short paragraph after it discussing the issue

These items are meant to provoke discussion among good-faith actors who take their ethical responsibilities seriously. You don't have to solve these problems; you just have to acknowledge any potential harm, no matter how unlikely. See Deon's [list of real-world examples](https://deon.drivendata.org/examples/) for each item.

As your project progresses, update this section with what you actually did to take the ethical considerations into account.

### Team Expectations

*Proposal and Checkpoints.* Read over the [COGS108 Team Policies](https://github.com/COGS108/Projects/blob/fa26/COGS108_TeamPolicies.md) individually. Then, include your group's expectations of one another for successful completion of your COGS108 project. Discuss and agree on what all of your expectations are. Discuss how your team will communicate throughout the quarter and consider how you will communicate respectfully should conflicts arise. By including each member's name above and by adding their name to the submission, you are indicating that you have read the COGS108 Team Policies, accept your team's expectations, and have every intention to fulfill them. These expectations are for your team's use and benefit — they won't be graded for their details.

### Teammate Roles

*Proposal.* You are not required to assign formal roles, but it may be worth discussing each member's strengths (e.g., coding, writing, finding and cleaning data, statistics, visualization, keeping the group organized, knowledge of your topic area) and considering what role each member might play on your team. The [Suggested ways to divide roles](https://github.com/COGS108/Projects/blob/fa26/COGS108_TeamPolicies.md#suggested-ways-to-divide-roles) section of the COGS108 Team Policies describes a few structures that have worked well. Roles can be shared and can change over the quarter, and taking on a role in an area you'd like to grow in is a great way to learn. Whatever you decide, every member is still responsible for understanding every part of the project. If your group decides not to assign roles, briefly note the strengths you discussed and how you plan to share the work. These notes are for your team's use and benefit — they won't be graded for their details.

### Project Timeline

*Proposal and Checkpoints.* Specify your team's specific project timeline, including a detailed schedule of dates/times for meetings that work for your group. An example timeline is provided in the template; change the dates, times, names, and details to fit your group's plan. **Update your timeline at each checkpoint** so we can see how your plans have changed.

### Discussion and Conclusion

*Final Report.* Wrap it all up in roughly **3-5 paragraphs**:

1. Summarize your important results.
2. Refer back to your Background section and discuss how this work extends previous work.
3. Bring the different results together into a bigger picture: what have we learned?
4. If results are confusing or contradictory, discuss how that might have happened.
5. Discuss the limitations of your work. For example: Is the dataset a biased sample? Would more data make you more confident? Would longitudinal instead of cross-sectional data be helpful? Is there evidence that the phenomena you're investigating may change over time?
6. Optionally, describe what the next steps might be if the work were to continue outside this class.

### AI and Outside Help

*All submissions.* Every notebook ends with a table recording the help your group received (see the [AI and Outside Help Policy](#ai-and-outside-help-policy)). Each group member fills in their own row(s), with one row for each instance of help, listing:

- **Group member:** who received the help
- **Section:** which section of the notebook it was for
- **Help from:** what person/website/AI the help came from
- **Type of help:** one or more of brainstorming, research, editing, drafting, concept, algorithm, partial code (help generating <50% of the code in a section), most code (help generating ≥50% of the code in a section), or debug
- **Description:** a brief description of what the help was

Every group member needs at least one row; if you did not receive any help, write "No help received." in the Section column of your row. In the Proposal, list help for the proposal. In each checkpoint, list help for new sections and for revisions to earlier sections (you don't need to repeat help you already listed). In the Final Report, list help **across the whole project**; you can copy your earlier entries and add new ones.

<sub>[↑ Back to contents](#contents)</sub>

---

## Grading

### Weights

| Component | Who | Percent of course grade |
|---|---|---|
| Project Proposal | Group | 5% |
| Data Checkpoint | Group | 5% |
| EDA Checkpoint | Group | 5% |
| Final Report | Group | 10% |
| Final Video | Group | 3% |

Individual grades may be adjusted based on the [Team Evaluation](#team-evaluation).

### How Rubrics Are Scored

Each notebook template begins with the full rubric for that submission (remember to delete that cell before you submit). Each rubric item is rated **Excellent**, **Proficient**, **Developing**, or **Unsatisfactory/Missing**. Items rated Excellent or Proficient lose no points; points are deducted for each Developing or Unsatisfactory/Missing item, until the score reaches 0.

| Submission | Rubric items | Each Developing | Each Unsatisfactory/Missing |
|---|---|---|---|
| Project Proposal (out of 10) | Research question, Background, Hypothesis, Data, Ethics, Team expectations, Timeline | −1 | −2 |
| Data Checkpoint (out of 10) | Data relevance, Data description, Data wrangling | −2 | −4 |
| EDA Checkpoint (out of 10) | EDA relevance, EDA analysis and description, EDA figures | −2 | −4 |
| Final Report (out of 15) | Title & abstract through Data wrangling | −0.5 | −1 |
| | Data visualizations through Documentation and written communication | −1 | −2 |
| Final Video (out of 3) | Video | −1.5 | −3 |

The Final Report rubric also includes a **quality modifier**: if almost everything is just barely proficient, with lots of minimal-effort work, it can cost 0.5 points (we won't double-penalize if you already lost points on the rubric); more than 5 Excellent ratings earns +0.5 points of extra credit.

### Earning Points Back

You will receive detailed feedback on each submission as GitHub Issues in your group repo. **If you address the feedback in a future checkpoint, you will earn those points back.**

To indicate to your grader what you have addressed, add a comment to the issue where points were initially lost explaining your changes. For this process to work, **all grading issues on GitHub must remain open**. Please do not close them.

<sub>[↑ Back to contents](#contents)</sub>

---

## Final Project Checklist

Students often ask what it takes to do well. The full rubric is in the first cell of `03-FinalProject.ipynb`; you can also use this checklist to help guide your thinking. If you check off all the boxes below, you should be in good shape for a perfect score on your final project.

**Title, Permissions & Video Link**
- [ ] Replace the template title with your project's title
- [ ] Mark YES or NO for permissions
- [ ] Add a link to your video, and test that it works in a private/incognito browser window

**Abstract**
- [ ] Write a clear summary of what you did
- [ ] Briefly describe the results of your project
- [ ] Limit abstract to 1 paragraph

**Authors**
- [ ] List every group member and their contributions (CRediT terms)

**Research Question**
- [ ] Include a specific, clear data science question
- [ ] Make sure what you're measuring (variables) to answer the question is clear
- [ ] Make clear what kind of analysis the question calls for (e.g., prediction vs. inference)

**Background and Prior Work**
- [ ] Include a general introduction to your topic
- [ ] Include explanation of what work has been done previously
- [ ] Include at least 3 relevant citations, cited inline
- [ ] Verify that every citation is real and says what you claim

**Hypothesis**
- [ ] Include your team's hypothesis
- [ ] Ensure that this hypothesis is clear to readers
- [ ] Explain why you think this will be the outcome (what was your thinking?)

**Data**
- [ ] Describe each dataset used (source, number of observations, relevant variables, shortcomings)
- [ ] Data are tidy and clean, or clearly demonstrated to be so
- [ ] Data loaded from `data/02-processed/`, with long wrangling code referenced in `01-DataCheckpoint.ipynb` rather than repeated

**Data Visualization**
- [ ] Include at least three relevant visualizations
- [ ] Clearly label all axes, legends, and titles
- [ ] Type of all plots appropriate given data displayed
- [ ] Reference and interpret each visualization in the text

**Exploratory Data Analysis & Analyses**
- [ ] EDA carried out with explanations of what was done and interpretations of output included
- [ ] At least two analyses beyond EDA, each technically appropriate
- [ ] Output of each analysis interpreted in the notebook

**Ethics**
- [ ] Every item in the Deon checklist considered and marked
- [ ] A short paragraph for each relevant item
- [ ] Describe how your group actually handled the ethical concerns

**Discussion and Conclusion**
- [ ] Clear conclusion (answer to the question being asked) and discussion of results
- [ ] Connect back to your background and prior work
- [ ] Limitations of analysis discussed
- [ ] Roughly 3-5 paragraphs; does not ramble on beyond providing necessary information

**AI and Outside Help**
- [ ] Table covers help received across the whole project
- [ ] Every group member has at least one row

**Video**
- [ ] Communicates the question and major results to a non-technical audience
- [ ] Effective visualizations presented
- [ ] Clear explanations throughout
- [ ] Take home message clear
- [ ] Within 3-5 min time limit

**Final Checks**
- [ ] Delete the rubric cell at the top of the notebook
- [ ] Remove all template instructions
- [ ] Edit all text for clarity
- [ ] Be sure text included throughout to guide reader
- [ ] Code evaluated, with all outputs, text, and images visible
- [ ] Code documented, with reusable code in `modules/`
- [ ] Final report is `03-FinalProject.ipynb`, pushed to your group repo by the deadline

<sub>[↑ Back to contents](#contents)</sub>

---

## After the Course

- If you checked YES to make your project public: your final report will be publicly visible. Your final report notebook (and only that!), including your names, will be placed in a public repo with the rest of this quarter's public reports. This helps future students by providing examples!
- Your project repo will remain available to you in the near future. We cannot guarantee that will always be the case. That repo will never be public.
- If you would like your own copy of the entire repo, follow [these instructions for duplicating a repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/duplicating-a-repository). Once you have done that it is yours forever. You will also be able to control access to the mirror (make it public or private as you would prefer).

<sub>[↑ Back to contents](#contents)</sub>

---

## Resources

### Advice

The main pieces of advice are:

* Start early
* Work consistently
* Be a good teammate
* Work as a team
* Seek advice when you are unsure, and seek it early and often!
* Talk to your TAs, IAs, and professor - we're here to help!
* Choose a general interest domain and question of interest, and then choose a dataset, not vice versa. I promise it will go much better.
* Start early!!!!!

As far as resources go, it is okay to ask other teams what they are doing in terms of sources, presentation plans, and so on. As long as you are not using another team's work and claiming it as your own, collaboration with classmates is encouraged. If you find a good source of datasets, please share with everyone on Piazza!

### Previous COGS 108 Final Projects

See Prof. Voytek's write-up of excellent class projects from the Spring 2017 instance of COGS 108 [here](https://voyteklab.com/data%20science/data-projects/), all of which received perfect scores.

Additionally, previous projects can be viewed from when this course ran in [Spring 2017](https://github.com/COGS108/FinalProjects-Sp17), [Winter 2018](https://github.com/COGS108/FinalProjects-Wi18), [Spring 2019](https://github.com/COGS108/FinalProjects-Sp19), [Fall 2019](https://github.com/COGS108/FinalProjects-Fa19), [Winter 2020](https://github.com/COGS108/FinalProjects-Wi20), [Spring 2020](https://github.com/COGS108/FinalProjects-Sp20), [Fall 2020](https://github.com/COGS108/FinalProjects-Fa20), [Winter 2021](https://github.com/COGS108/FinalProjects-Wi21), [Spring 2023](https://github.com/COGS108/FinalProjects-Sp23), [Winter 2024](https://github.com/COGS108/FinalProjects-Wi24), [Winter 2025](https://github.com/COGS108/FinalProjects-Wi25). Note first, that these projects are of variable quality and second, that if you get inspiration or code from previous projects, this must be noted in your project, giving attribution to the former groups' work.

### How to Find Datasets

The purpose of this project is to find a real-world problem and dataset (or likely, datasets!) that can be analyzed with the techniques learned in class and those you learn on your own. It is imperative that by doing so you believe extra information will be gained — that you believe you can discover something new! (See [Data Requirements](#data-requirements) for the minimum dataset size.)

The best datasets are the ones that can help you answer your question of interest.

Your question could be just for fun: Using text mining of song lyric websites to identify the most commonly used phrases and sentiments by decade.

Your question could be scientific: Scrape data from animal taxonomies and Wikipedia to figure out if larger animals are more likely to be carnivores.

Or, ideally, your question can be aimed at civic or social good, for example, use mapping, transit, and car accident data to identify which parts of San Diego are most in need of dedicated bike lanes.

Eventually you will all have to decide on a problem to tackle, with each member of the team having a clear, delineated role in the project.

<details>
<summary><b>Dataset Resource List</b> (click to expand)</summary>

Here is a list of potential locations to find datasets and problems to investigate. If you have another dataset or search location, that is great!

**Search engines & large repositories**
* [Google Dataset Search](https://datasetsearch.research.google.com/)
* [Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets/blob/master/README.rst)
* [Kaggle](https://www.kaggle.com/)
* [UCI Machine Learning Repository](https://archive.ics.uci.edu/)
* [Hugging Face Datasets](https://huggingface.co/datasets) (text, image, and audio data; good for NLP projects)
* [data.world](https://data.world/)

**Curated collections** (great for finding less common topics)
* [TidyTuesday](https://github.com/rfordatascience/tidytuesday) (a new, already-cleaned dataset every week)
* [Data Is Plural](https://www.data-is-plural.com/archive) (weekly newsletter archive; also available as a [spreadsheet](https://docs.google.com/spreadsheets/d/1wZhPLMCHKJvwOkP4juclhjFgqIY8fQFMemwKL2c64vk/edit#gid=0))
* [Data and Story Library](https://dasl.datadescription.com/datafiles/)
* [FiveThirtyEight](https://data.fivethirtyeight.com/) (no longer updated: FiveThirtyEight shut down in 2025, but its existing datasets are still available)

**Government & economic data**
* [Data.gov](https://catalog.data.gov/dataset)
* [US Census](https://www.census.gov/)
* [California Open Data](https://data.ca.gov/)
* [San Diego Data](https://data.sandiego.gov/)
* [World Bank Open Data](https://data.worldbank.org/)
* [FRED (Federal Reserve Economic Data)](https://fred.stlouisfed.org/)

**Social science & survey data**
* [IPUMS](https://www.ipums.org/) (census and survey microdata; free account required)
* [ICPSR](https://www.icpsr.umich.edu/) (large social science data archive; free account required, and some data are restricted to member institutions)
* [Pew Research Center Datasets](https://www.pewresearch.org/datasets/)
* [Stanford | Social Science Data Collection](https://data.stanford.edu/)
* [Eviction Lab (email required)](https://evictionlab.org/get-the-data/)

**Science, health & environment**
* [Our World in Data](https://ourworldindata.org/) (global health, economic, and environmental indicators; every chart can be downloaded as CSV)
* [Open Climate Data](http://openclimatedata.net/)
* [UCSD behavioral mobile data](http://extrasensory.ucsd.edu/)

**More lists of data sources**
* [UCSD Datasets](https://ucsd.libguides.com/data-statistics/home) (UC San Diego Library guide)
* [Free Datasets - R and Data Mining](http://www.rdatamining.com/resources/data)

</details>

<sub>[↑ Back to contents](#contents)</sub>
