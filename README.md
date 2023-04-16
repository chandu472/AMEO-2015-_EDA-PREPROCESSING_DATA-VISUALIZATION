# AMEO-2015-_EDA-PREPROCESSING_DATA-VISUALIZATION

### Aspiring Mind Employment Outcome 2015 (AMEO)

#### Data Description
The Aspiring Mind Employment Outcome 2015 (AMEO) dataset contains the employment outcomes of engineering graduates in India from the graduating batch of 2015. The dataset was created by Aspiring Minds, an Indian employability evaluation and certification company. The dataset consists of 40 variables and 3998 observations.

The variables in the dataset include:
ID: Unique identifier for each graduate.

Salary: The annual salary in INR (Indian rupees) offered to the graduate.

Gender: Gender of the graduate.

Age: Age of the graduate at the time of graduation.

DOB: Date of birth of the graduate.

10percentage: The percentage marks obtained in the 10th grade.

12graduation: Year of graduation in 12th grade.

12percentage: The percentage marks obtained in the 12th grade.

CollegeID: Unique identifier for the college where the graduate studied

CollegeTier: Tier of the college where the graduate studied (1 or 2). . Degree: The degree obtained by the graduate (B.Tech or M.Tech).

Specialization: The specialization of the degree obtained by the graduate.

CollegeGPA: The GPA obtained by the graduate during their college education.

CollegeCityID: Unique identifier for the city where the college is located.

CollegeCityTier: Tier of the city where the college is located (1, 2, or 3).

GraduationYear: Year of graduation.

English: Score obtained in the English language assessment.

Logical: Score obtained in the logical reasoning assessment.

Quant: Score obtained in the quantitative aptitude assessment.

Domain: Score obtained in the domain knowledge assessment.

ComputerProgramming: Score obtained in the computer programming assessment

ElectronicsAndSemicon: Score obtained in the electronics and semiconductor assessment.

ComputerScience: Score obtained in the computer science assessment.

MechanicalEngg: Score obtained in the mechanical engineering assessment.

ElectricalEngg: Score obtained in the electrical engineering assessment.

TelecomEngg: Score obtained in the telecommunications engineering assessment.

CivilEngg: Score obtained in the civil engineering assessment.

Conscientiousness: Score obtained in the conscientiousness assessment.

Agreeableness: Score obtained in the agreeableness assessment.

Extraversion: Score obtained in the extraversion assessment.

Nueroticism: Score obtained in the neuroticism assessment.

Openness_to_experience: Score obtained in the openness to experience assessment.

HighSchoolPercentage: Percentage marks obtained in high school.

HighSchoolBoard: The board of high school education.

HighSchool: The name of the high school.

Location: The location where the graduate is currently working.

CollegeState: The state where the college is located.

GraduationSpecialization: The specialization of the degree obtained by the graduate at the time of graduation.

Employee ID: The ID assigned to the employee at their current workplace.

#### Objective
The objective of this dataset is to explore the various factors that contribute to the employment outcomes of engineering graduates in India. The dataset can be used to perform exploratory data analysis (EDA) to identify trends and patterns in the data, and to gain insights into the factors that are associated with higher salaries and better employment outcomes.

Some of the questions that can be explored using this dataset include:
How does the percentage of marks obtained in high school and 12th grade relate to the salary offered to the graduate?

Is there a difference in salary offered to graduates of Tier 1 and Tier 2 colleges?

How does the graduate's performance in domain knowledge, computer programming, and other assessments relate to their employment outcomes?

What is the relationship between the graduate's personality traits (conscientiousness, agreeableness, extraversion, neuroticism, and openness to experience) and their salary and employment outcomes?

Are there any differences in employment outcomes between male and female graduates?

Which cities and states have the highest average salaries for engineering graduates?

In summary, the Aspiring Mind Employment Outcome 2015 (AMEO) dataset is a rich dataset that can be used to perform exploratory data analysis to gain insights into the employment outcomes of engineering graduates in India. By analyzing the various factors that contribute to employment outcomes, we can identify trends and patterns in the data and gain a better understanding of the factors that are associated with higher salaries and better employment outcomes.

#### Overall Conclusion

Based on the analysis of the AMEO 2015 dataset, we can draw the following conclusions:

The DOJ, DOL, and DOB columns are given in timestamp format and need to be converted to dates for our analysis.

The Job city column contains NaN equivalents, which need to be cleaned.

The 10th and 12th board columns, college state column, graduation year column, and domain column contain missing values that need to be addressed.

The salary data is right-skewed and contains many outliers.

Male and female distributions for salaries below 10 lakhs are quite similar.

Median salaries for male and female categories are similar, but males have more outliers, indicating more people are getting higher pay in male categories.

Median salary of people from all specializations are nearly similar, but more people getting higher pays have specialization in CS/EC compared to others.

Male-dominated IT roles are the most frequent roles taken by AMCAT aspirants, and their distributions are considerably different from the other general roles.

Mean salary of top most frequent roles is nearly independent of gender, but there are some considerable differences in some roles.

Joining of male employees is higher than female employees in all the years, and the highest joining year is 2013.

Most of the high-paying jobs are from the IT domain, and in 45% of top-paying roles, men are paid higher compared to women.

For the same amount of experience, men are paid slightly higher than women in most cases, and men have more highly paid jobs compared to women for every level of experience.

Men from CS/EC/CE earn slightly greater than women from these specializations, but women from the EL specialization earn more than men from the same specialization.

Both male and female distributions for college GPA are normally distributed, with the mean around 75%, and there is no relation between high or low GPA and salary.

The percentages of 10th and 12th grades are substantially positively associated with one another, as are the topics English, Logic, and Quant.
