# Health Disparities in Transgender People in the U.S. | Simon Mack

## Executive Summary
As a transgender person, equality in healthcare for transgender people is important to me. In this project, I cleaned and analyzed the CDC’s 2019 Behavioral Risk Factor Surveillance System Survey to determine which U.S. regions have the greatest health disparities between transgender and cisgender people as well as where health disparities exist among transgender people of different demographics. For the purposes of this project, I measured health disparity by the difference between the percent of transgender people with poor health and the percent of cisgender people with poor health.

My assumptions going into this project were that there are significant health disparities between transgender and cisgender people, especially among trans women of color in the Midwestern and Southeastern United States. I was right and wrong. You can see my findings below.


## Motivation
I’m a transgender person, and even with the privilege I have as a white, male-passing person, my experience navigating healthcare has been difficult. I want to gain insights on where health disparities exist between transgender and cisgender people (and among trans people of different demographics) to provide a path forward in bettering the health outcomes of transgender people in the U.S.


## Data Questions
Are there health disparities between transgender and cisgender people in the U.S.? If so, what regions have the greatest health disparities between transgender and cisgender people? Where are there health disparities among transgender people of different demographics? How might these disparities be reduced?


## Data Sources
My data is the CDC’s 2019 Behavioral Risk Factor Surveillance System Survey, a survey that collected state data about U.S. residents regarding their health-related risk behaviors, chronic health conditions, and use of preventive services. More than 418,000 people were surveyed, including almost 1,000 transgender people.


## Intended Audience
The example intended audience of this analysis is the GMLA: Health Professionals Advancing LGBTQ Equality. The presentation and dashboard are intended to help them decide where to focus their efforts to ensure equality in healthcare for transgender individuals and healthcare professionals.


## Methodology
1. Retrieved data and converted from XPT to CSV
2. Cleaned and categorized data in Python
3. Defined key measures
4. Calculated key measures in Python
5. Created [interactive dashboard in Tableau](https://public.tableau.com/shared/ZF39M6W3H?:display_count=n&:origin=viz_share_link), validating measures with Python throughout
6. Created Google Slides presentation to accompany the dashboard


## Findings


### Disparities Between Transgender and Cisgender People
- Trans people are more likely than cis people to have poor health in every U.S. region
- The greatest health disparities between cis and trans people are in the Midwest and Northeast
- The region with the least health disparity between cis and trans people is, surprisingly, the South


### Disparities Among Transgender People
- Groups of trans people at the highest risk of having poor health:
  - Didn't graduate high school
  - Earn less than $15,000 annually
  - Are unable to work
  - Are age 54 to 65
  - Are gender nonconforming
  - Are gay

- Another surprise: white, non-Hispanic trans people are more likely to have poor health than Hispanic trans people and/or trans people of color (though not by much)
- Trans people who are unable to work are more than 9 times as likely to have poor health than employed trans people
- Trans people who didn’t graduate high school are almost 4 times as likely to have poor health than trans people who graduated from college or technical school
- Gender nonconforming trans people are almost twice as likely to have poor health than trans men, with trans women falling in the middle
- Straight trans people are less likely to have poor health than gay trans people, but are more likely to have poor health than bisexual trans people


### Potential Action Areas
- Transgender people are more likely than cisgender people to:
  - Not have seen a doctor because of cost in the past year*
  - Not have healthcare coverage*
  - Not have a personal doctor
  - Not have had a routine checkup in the past year*

- A good start to reducing these disparities and the others we’ve covered would include:
  - Focusing extra efforts and resources on trans people in the Midwest and Northeast
  - Focusing extra efforts and resources on the high risk demographic groups of trans people we covered
  - Focusing extra efforts and resources on ensuring trans people have access to healthcare coverage and knowledgeable primary care physicians

*Especially among trans people with poor health
