# Data Professionals Survey Analysis

Used tools: PowerBI

Project Type: Data cleaning, Exploratory data analysis, Data visualization

## Detailed Report
### Table of Contents
[Project Overview](#Project-Overview)

[Data Cleaning](#Data-Cleaning)

[Executive Summary](#ExecutiveSummary)

[Insight deep dive](#Insight-deep-dive)
- Preferred programming language by data professionals
- Data professional's salary by industry
- Countries with the most paid by role
- Educational influence on salary earned by data professionals
#### Recommendations


## Project Overview

This dataset consists of a data professional survey by Alex Freberg, a YouTuber known as Alex the Analyst. The survey was taken by 630 individuals from four countries; 41% from the USA, 12% from India, 6% from the UK, 5% from Canada, and 36% without their specific countries. The average age of the survey takers is 30 years, and the gender split is 74% male and 26% female. The survey consists of the following questions
- which best fits your current role?
- Did you switch careers to data
- Current yearly salary (in USD)
- What industry do you work in
- Favourite programming language
- How happy are you in your current position
- How difficult was it for you to break into data
- which country do you live in
- Highest education level
- Current age


## Data Cleaning
The data was cleaned using powerBI power query editor.
#### Data cleaning steps
- The input "others" by survey takers were filtered out to make the analysis and visualization sensible
- Multiple programming language imputed by survey takers were delimited to have a single input
- the salary range was converted to a single value for a measurable analysis

## Executive Summary
The data professional survey recorded in 20222 shows that, data professionals prefer Python programming language with 310 counts of survey takers followed by R with 67. United States tends to pay data scientists higher with an average salary of $139K followed by data Engineers with $101K. United Kingdom has the lowest paying salary of $47K for data Engineers and $20k for database developers. The educational level has proven to have a significant effect on salary as a PhD earned an average salary of $125K followed by a Masters with $61K respectively.

## Insight deep dive
#### preferred programming language by data professionals
About 310 survey takers prefer Python as their favorite programming language, followed by R with 67 and Javascript being the least with 2.



![fav](https://github.com/user-attachments/assets/32b3b8e6-866e-405c-9a59-d5b511df6a7d)

#### Data professional's salary by industry
Education tends to pay higher with $67K, healthcare with $64K, and telecommunication with a lowest paying salary of $44K.

![idu](https://github.com/user-attachments/assets/0d823791-b86a-4017-836d-d75065782f98)

#### Countries with most paid by role
USA recorded the highest paid salaries across all job titles with $139K for data Scientists, followed by Canada with $105K for data engineers, and the United Kingdom with the lowest paying salaries of $47K for data engineers and data analyst
![jo t](https://github.com/user-attachments/assets/ce475e33-20e2-4c54-be59-5502f9bb10a1)

#### Educational influence on salary earned by data professionals
The level of education has proven to have a significant effect on the salary earned by data professionals, as PhD holders earn as much as $125K annually followed by Masters and associates with the least paying salary of $43K.

![salary](https://github.com/user-attachments/assets/8bc36148-abcb-473e-b331-a08adbafa270)

#### Difficulty breaking into data
43% of survey takers agreed that it is indeed difficult breaking into data with 37% disagreeing that it is easy

![diff](https://github.com/user-attachments/assets/6f795931-f632-4667-b4aa-7c7596682129)

#### Recommendations
1. For a better paycheck, data professionals can focus on industries like Education (67K), Healthcare (64K), and Real Estate (63K) for higher salary prospects.
2.  Since the U.S. offers the highest salaries across job titles, data professionals could explore remote job opportunities with U.S.-based companies or consider relocation if feasible. Additionally, building a strong LinkedIn profile and networking within the U.S. market could increase visibility to potential employer
3. Since advanced degrees like a PhD (125K) or a Master's (61K) significantly influence salary, data professionals could consider furthering education if it's aligned with their career goals. Alternatively, they could pursue specialized certifications that may offer similar advantages.
4.  Given that Python is the most preferred programming language, data professionals should prioritize mastering it. 
5.  Since 43% find breaking into the data career difficult, professionals could focus on engaging in continuous learning, Participating in hackathons, attending webinars, and networking within the data community to access valuable exposure and opportunities.

The full dashboard can be found [here](#datasurveydashboard)

