# E-News-project
Problem Statement:
An online news portal aims to expand its business by acquiring new subscribers. Every visitor to the website takes certain actions based on their interest. The company plans to analyze these interests and wants to determine whether a new feature will be effective or not. Companies often analyze users' responses to two variants of a product to decide which of the two variants is more effective. This experimental technique is known as a/b testing that is used to determine whether a new feature attracts users based on a chosen metric.
Suppose you are hired as a Data Scientist in E-news Express. The design team of the company has created a new landing page. You have been assigned the task to decide whether the new landing page is more effective to gather new subscribers. Suppose you randomly selected 100 users and divided them equally into two groups. The old landing page is served to the first group (control group) and the new landing page is served to the second group (treatment group). Various data about the customers in both groups are collected in 'abtest.csv'. Perform the statistical analysis to answer the following questions using the collected data.
On this study I will conduct a/b testing to understand the data inferences, and recommend the necessary insights on the effectiveness of the new page on attracting users considering their different chosen metrics.
Objectives:
As a data scientist chosen to conduct this study. The mail goal is to do an a/b testing experiment for this I will be conducting statistical analysis of the business data that have been provided to best answer the questions and needs of the company. Throughout this study several main questions will be address such as:
Explore the dataset and extract insights using Exploratory Data Analysis.
Do the users spend more time on the new landing page than the old landing page?
Is the conversion rate (the proportion of users who visit the landing page and get converted) for the new page greater than the conversion rate for the old page?
Does the converted status depend on the preferred language?
Is the mean time spent on the new page same for the different language users?
The Level of significance given for all tests in this study is 0.05
Data Dictionary:
user_id - This represents the user ID of the person visiting the website. group - This represents whether the user belongs to the first group (control) or the second group (treatment). landing_page - This represents whether the landing page is new or old. time_spent_on_the_page - This represents the time (in minutes) spent by the user on the landing page. converted - This represents whether the user gets converted to a subscriber of the news portal or not. language_preferred - This represents the language chosen by the user to view the landing page.
