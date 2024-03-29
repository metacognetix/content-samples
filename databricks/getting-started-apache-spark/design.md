![Databricks logo](assets/databricks-black.png)
# Lesson Design
## Getting started with Spark when you know SQL

| Last updated | 2019-12-09 |
| --- | --- |
| Author | Jeff Brockway |
| Curriculum | Moving your data analytics from database to Databricks |
| Course | Working with data in Apache Spark |
| Lesson | Getting started with Spark when you know SQL |

---
## Assumptions & objectives

#### Learner profile
Citizen data scientist - Someone who has the technical skills to understand the business need for analytics and is skilled in extracting that information from spreadsheet transformations, pivot grids, SQL queries from relational databases, or database report authoring.

#### Synopsis
Help someone familiar with traditional database analytics and reporting understand the need for big data and how the concepts map, with a hands-on example for context.

#### Assumptions
* User has already set up a Databricks account
* User has already created a cluster

#### Primary objective
* Learn big data concepts with Spark and Databricks

#### Learning objectives
* List six use cases for big data
* List four primary tools used for big data analytics
* Map small data concepts and tools to big data
* Describe the three primary Spark dataset types
* Create and navigate a Databricks notebook
* Import a dataset
* Describe transformations and actions
* Use visualizations
* Save and share notebooks
* Identify next steps




---
# TODO
* Check against my standard design document
* Make design doc template
* Create storyarc curriculum plan
* Automate build and publish with github actions

## Intro
* Not a data scientist or an engineer
* New to big data/DA/DB/Spark
* Have done some learning on ML
* You're going to have to help me on what I got wrong

## Follow-up
* Making of
* SCORM interface to revealjs
* Check on the learning objectives against the content

## CTA
* Link to github
* Link to reveal and SCORM articles


---
## Outline

#### You are here
* Where you are in the Course
* What you've already done
* What you'll walk away with



#### Why big data?
Not all jobs can run once daily on a single system



#### When would I use it?
1. When it's too big to run on one machine
2. When you need it faster



#### What are some use cases?
* Cyber security SIEM systems
* Too many events
* You’re going to need some help



#### What tools will I use?
* Apache Spark
* Databricks
* other tools



#### How does that compare to what I know?
* SQL DB --> HDFS, DBFS, Delta Lake
* data --> clustered fs (in memory)
* SQL --> Spark
* Shell --> Notebooks
* Apps --> Notebooks
* Code --> Notebooks
* Reporting --> Notebooks

notes:
#### Making the leap
Moving from relational database data analytics to big data
like moving from procedure programming to object oriented. It's a big leap.

* data --> clustered fs (in memory)
* SQL --> Spark
* Shell --> Notebooks
* Apps --> Notebooks
* Code --> Notebooks
* Reporting --> Notebooks



#### Couldn't I just write a SQL query?
* You can use SQL
* Consider your infrastructure
* How do you scale?



#### So what is Apache Spark?



#### Ok, so how do I install this on my machine?
* Er, you don't



#### Where does Databricks fit in?
* Infra structure
* Clustering and scalability
* Job running
* UI and Notebooks
* Reporting



#### How do I get started?
First get some data scientist a on it to explore, and then data engineers to plumb it

* Where is your data now?
* How did it get there?
* How did you transform it?
* What happens when it updates?
* What happens when the schema changes?
* How do you know you are seeing the possibilities?
* Log into Databricks
* Access data sets



# Hands-on practice



* Sign up for Databricks CE



* Import a dataset



* View the data



* Perform some actions on it



* Perform some transformations



* Do this with SQL and Python



* Visualize



* Save and share notebook



#### Next steps

---

## Notes
