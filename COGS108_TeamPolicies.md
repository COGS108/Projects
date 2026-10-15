# COGS108 TEAM POLICIES

Teams sometimes struggle to function as a team rather than a few individuals doing work and everyone else barely helping. The goal of this document is to help you make it more likely that your team works together.

### Organizing a team
Teams need structure. If people know the structure then they can meet expectations.

Give your team structure in these ways:
1. Set expectations around communication. How/what app (Discord, WhatsApp, Email)? How long is reasonable to wait before you expect a response to a message? How frequently will you meet (I suggest weekly or twice a week!)? Virtually or in person?
2. Set expectations around tone.  Some people are shy or struggle to express their opinions directly.  Other people are blunt to the point of sounding rude. Different cultures have different norms around how you say something, especially if its critical.  You should all agree on what tone you expect, and I personally suggest something like "blunt but polite". An example would be "I think X is a problem because of Y. Does everyone else see it that way too or am I missing something?" Another example is "I disagree with that idea, because Z. What do you think if instead we try..."
3. Set expectations around decision making.  Will everything be a unanimous or majority vote?  Or will you delegate authority for different kinds of decisions to different people? What if a decision has to be made in a short time frame and a teammate is non-responsive?
4. Set expectations around tasks.  Will there be specialization (leadership, facilitator/communicator, programming, research, etc)? Or will everyone do a bit of everything? Or a middle ground, where people specialize but rotate roles each week? How will tasks be assigned to people?  How can your whole team see the list of current tasks and see progress on them (GitHub Issues, Kanban board, Trello, Google spreadsheet)?
5. Make a plan, set a schedule/deadline for each planned item. Keep it updated as the plan changes.
6. Make a set of policies about what you will do when someone is struggling to deliver something they promised to do.  How should a struggling person contact the group? How soon after they start struggling?  How will the group allocate effort to make up for the issue?
7. Post these expectations somewhere for all to see.  Most of these are supposed to be part of your project proposal, but it may be helpful to have these in a shared document or something like the #Rules channel on a Discord server


It is very helpful if you address all of these topics in your first meeting!

### Contributing to your team

While one member may contribute more to a specific portion of the project and less to others, all members should be contributing equally in terms of effort across the entire project . For example, one group member may find the datasets you’ll end up using in the project and will write the code to wrangle the dataset into the format you want. However, that person should NOT write all the code in the project. Another member would then contribute the draft of the code to visualize the data, while yet another member would edit and improve upon that code. This project is meant to be a collaborative. But, in a successful collaboration, all participants must carry their weight and contribute equally. 

And critically you must communicate with your team.  Even if you do a lot, if you don't communicate with your team they may feel like you contributed little.

Everyone should contribute in some way or another to each of the following project aspects:

* Deciding on the project topic, searching for possible datasets, and honing the data science question.
* Writing well-commented and clear code to wrangle, explore, visualize, analyze, and communicate your groups' findings.
* Writing the accompanying text throughout the project to explain each section.
* Editing the text and code throughout your project for grammar, misspellings, and clarity.

While portions of the project can and should be done individually or in pairs (it's not easy to have five people working on code for the same section at once!), your team should assign tasks and deadlines evenly across members. Regular meeting times throughout the quarter should be scheduled in advance to check in with one another, discuss progress, see if the project is on task, and see if anyone is stuck. The best approach is to discuss each person's strengths up front, divide up responsibilities, develop a schedule for when each part will be done and who will be responsible for each section, and then check in regularly throughout the quarter to ensure progress is being made. To guide this, your proposal includes a Teammate Roles section, where you'll discuss each member's strengths and possible roles, and a Project Timeline, where you'll lay out a plan with tasks assigned to each person in the group. 

Upon submission, the names of every team member who participated actively in completing it should be included on the submission.

### Suggested ways to divide roles

Item 4 under [Organizing a team](#organizing-a-team) asks how your team will divide tasks. You are not required to assign formal roles, but it's worth discussing each member's strengths and considering what role each person might play. Below are a few structures that have worked well for projects like this one. If you use one (or mix and match), note it in the Teammate Roles section of your proposal and revisit it at each checkpoint. Whatever you choose, remember that **everyone still contributes to every aspect of the project** (see above): a "lead" coordinates and makes sure their area gets done well, but does not do all of that work alone.

**1. Rotating roles.** Each person takes one role per submission, and roles rotate at every submission (Proposal → Checkpoint #1 → Checkpoint #2 → Final Report) so everyone does a bit of everything. Example roles:

* *Coordinator*: runs meetings, keeps the task list and deadlines up to date, and makes sure the submission is turned in on time
* *Data lead*: finding, loading, and cleaning data
* *Analysis & visualization lead*: EDA, analyses, and figures
* *Writing lead*: makes sure the text reads clearly from start to finish and that each section explains what was done and why
* *Reviewer*: checks the submission against the guidelines and [checklist](https://github.com/COGS108/Projects/blob/fa26/FinalProject_Guidelines.md#final-project-checklist), runs the notebook top to bottom, and proofreads

For a 4-person team, combine Coordinator and Reviewer.

| | Proposal | Checkpoint #1 | Checkpoint #2 | Final Report |
|---|---|---|---|---|
| Member A | Coordinator | Reviewer | Writing lead | Analysis lead |
| Member B | Data lead | Coordinator | Reviewer | Writing lead |
| Member C | Analysis lead | Data lead | Coordinator | Reviewer |
| Member D | Writing lead | Analysis lead | Data lead | Coordinator |
| Member E | Reviewer | Writing lead | Analysis lead | Data lead |

**2. Section owners with reviewers.** Each person owns specific sections of the notebook (both the code and the text) and is a second reviewer on someone else's section. For example: Background & Prior Work and Hypothesis; Dataset(s) and Data Cleaning; EDA; Analysis; Ethics & Privacy and Conclusion. Assign sections so that everyone writes some code, and consider swapping ownership between checkpoints.

**3. Split by dataset or sub-question.** If your project combines multiple datasets or has a few sub-questions, pairs (or individuals) can each own one dataset or sub-question end to end: cleaning, EDA, and analysis. Plan regular meetings to bring the pieces together, and agree early on how the datasets will be combined and how shared variables will be named.

**Roles worth assigning regardless of structure**

* *Notebook manager*: Jupyter notebooks are hard to merge on GitHub, and two people editing the same notebook at once often leads to merge conflicts or a broken file. Consider having everyone work in their own scratch notebooks (or branches), with one person responsible for copying finished work into the official notebook (for example, `FinalProject_GroupXXX_FA26.ipynb`). Always pull before you start working and push when you finish.
* *Facilitator*: see [Communicate well](#communicate-well) below.
* *Video producer*: coordinates the final video (script, recording, editing) while making sure every member participates.

### Communicate well

I statements can be very helpful when talking with others... "I think this won't work because... what do you think?" may help more than "This won't work."

When someone expresses a criticism of your ideas or work try to understand why they think that way.  Assume that criticism is well-meant.  After all, if someone actually thought that you were personally worthless it wouldn't be worth their time and effort to criticize.  They must at least see the potential for improvement or perhaps the core of something great with a few changes.

It can be very helpful if at least one group member with high emotional IQ tries to take on the role of facilitator... someone who can translate between different cultures... someone who can try to make the quiet people feel safe enough to talk, and who can kindly remind the talkers that they should allow other people time to express themselves.


### Dealing with conflict

Group work isn’t always easy - Team members sometimes cannot prepare for or attend group sessions because of other responsibilities, and conflicts often result from different skill levels and work ethics. One way to improve the chances that a team will work well is to agree beforehand on what the team expects from everyone else, and also how you will deal with problems. Reaching this understanding before problems happen helps. 

Everyone approaches conflict a little differently. But there are some common themes that might be seen in a person's response again and again. Learning how you approach conflict can be a great opportunity to learn or refine successful conflict resolution. To learn more about your conflict approach, and how it interacts with your teammates approach you can each take this quiz. https://cuboulder.qualtrics.com/jfe/form/SV_6Kkp5kCHt628Zg1

Other helpful resources for dealing with conflict in group projects are https://www.beyondintractability.org/educationtraining/group-projects and https://www.cmu.edu/teaching/solveproblem/strat-groupwork/groupwork-04.html and the citations therein.


### Dealing with problem teammates

Toward the end of the course, you will be sent a survey to evaluate the team’s progress as well as each member in the group’s contributions.  This form will be collected and considered when your grade is calculated at the end of the quarter. People who don't do their fair share will get fewer points, and people who do more than their fair share may get extra points.  Therefore you should be motivated to make sure you are not seen as a slacker by your teammates!

If a team member refuses to cooperate or complete their assigned tasks that you all have agreed upon on the project, you should first inform the uncooperative team member via email (or some other form or written communication) that they have not been pulling their weight and that they'll need to demonstrate significant improvement within a week, spelling out specifically what must be completed (i.e. edit code for wrangling section, write discussion, etc.). If there is no subsequent improvement, the team members should notify the professor. This can be a DM or an email to the professor individually . Please include details and specifics. Note that teams should be working steadily throughout the quarter on their projects. The professor should know of any ongoing issues by week 7 at the latest.

