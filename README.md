# Nurse Resilience

This project examines burnout and resiliency in nurses, anesthesiologists (national data sets) and advance practice nurses (VUMC wide data set) and has over 6,000 respondents. 

### Prerequisites
To most easily run this code out of the box, the following packages must be installed:
* pandas
* numpy
* scikit-learn
* matplotlib
* seaborn
* great expectations
* h2o
* fastai

This is easiest to achieve through first installing an Anaconda distribution, which installs the first 5 packages and all of their dependencies.  The install directions to the other packages may be found on their documentation pages.

# Quick navigation
[Background](#background)  
[Data](#data)  
[Models](#models)  
[Timeline](#timeline)  
[Logistics](#project-logistics)  

# Goal

Provide an overview of the goals and deliverables of the project. Mention any relevant details or issues. 

# Background  

We created (and have since validated) the Self Identify Burn Out survey (SIBO) that allowed us to categorize respondents as currently burnout out, never burned out or formerly burned out. Burnout has never been examined in this way before our projects. Identification of those who have completed this  journey through an episode of burnout and are still working within the healthcare, is critical in understanding resiliency.  
We wanted to identify actionable items, things that contributed to resiliency that organizations as well as individuals could do to contribute to a work environment that nurtures resiliency. Only because we could not locate an instrument that was already validated, we created and have tested our Social Support and Personal Coping survey  (SSPC) to identify practices that contribute to resiliency. We are currently working on validating this instrument. Through this work we have identified specific types of support and personal coping practices that do contribute to resiliency. However we have a large amount of free text responses to our hobby data information. We have found specific types of hobbies are very beneficial from the checklist in our survey, but do  not know if the free text “other” hobbies belong into the categories the team has previously created or if there exists a new category.
We are seeking support in using natural language or word stemming analysis to assist us in the validation. The 6,000 respondents we currently have collects are all pre-covid, we are currently gathering covid data that we could create a second analysis for later this summer. We anticipate that the hobbies have changed due to covid, for example perhaps the movie goers are now hiking.

# Data

Describe the data - what kind of data is it?  Describe the general format, and potential quirks.

## Data security

If there are any security concerns or requirements regarding the data, they should be described here.

## Counts

Describe the overall size of the dataset and the relative ratio of positive/negative examples for each of the response variables.

# Models

Clearly identify each of the response variables of interest.  Any additional desired analysis should also be described here.

# Timeline

Outline the desired timeline of the project and any explicit deadlines.

# Repo Structure 

Give a description of how the repository is structured. Example structure description below:

The repo is structured as follows: All *0- (e.g., 10-, 20-, 30-) files contain finalized work for the purpose described (e.g., "process-data"). Subfiles related to the task (e.g., 11-, 12-) should be created in order to explore and document relevant or interesting subtasks.

All files which appear in the repo should be able to run, and not contain error or blank cell lines, even if they are relatively midway in development of the proposed task. All notebooks relating to the analysis should have a numerical prefix (e.g., 31-) followed by the exploration (e.g. 31-text-labeling). Any utility notebooks should not be numbered, but be named according to their purpose. All notebooks should have lowercase and hyphenated titles (e.g., 10-process-data not 10-Process-Data). All notebooks should adhere to literate programming practices (i.e., markdown writing to describe problems, assumptions, conclusions) and provide adequate although not superfluous code comments.

# Project logistics

**Sprint planning**:  
**Demo**:  

**Data location**:  

**Slack channel**:  
**Zoom link**:  

# Resources 

Provide links to any resources that may be useful in running the repo (python/git/accre tutorials etc).

# Contact Info

Add contact information for any project stakeholders. Include name, email and title. 
