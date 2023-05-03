The goal for this project was to identify and justify a list of the top twenty institutions that INTO University should partner with that is:
- Located in the USA
- Highly attractive to international students
- In a state with no current partners
- Is relatively affordable for undergraduates
- Present an opportunity for recruiting international students at scale

Here is a breakdown of the project:

### 1. Preparation  
Two sources of data were used for this project, IPEDS https://nces.ed.gov/ipeds/use-the-data/download-access-database from the National Center for Education Statistics, and CollegeScorecard https://collegescorecard.ed.gov/data/ from the US Department of Education. The former was provided in a Google BigQuery database as part of the project, whilst the latter was manually imported.

This stage involved joining the relevant tables and datasets together, as well as some minor cleaning.

<-- Replacing non-integer values in quantitative columns
<-- Casting all quantitative columns to integers, 

### 2. Analysis 
Then, I analysed the data with SQL queries and Excel.

### 3. Visualisations 
To visualise the analysis results, I used Power BI to create two interative dashbaords - one comparing the recommended list against current partners, and the other against in-state competitors.
![Dashboard 1](images/Dashboard_1.png)
![Dashboard 2](images/Dashboard_2.png)

### 4. Business Case
This document covers the project problem, findings, recommendations, and potential risks. It was sent to the stakeholder before the next stage.
![Business Case](Business_Case.pdf)

### 5. Presentation Slides
This covered  a summary of the project, focusing on the the top 5 recommended institutions from the analysis, and was used to deliver a presentation to the stakeholder. 
![Slides](Slides.pdf)