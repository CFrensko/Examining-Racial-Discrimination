# Examining-Racial-Discrimination

Examining Racial Discrimination in the US Job Market

Background:

Racial discrimination continues to be pervasive in cultures throughout the world. Researchers examined the level of racial discrimination in the United States labor market by randomly assigning identical résumés to black-sounding or white-sounding names and observing the impact on requests for interviews from employers.

Data:
In the dataset provided, each row represents a resume. The 'race' column has two values, 'b' and 'w', indicating black-sounding and white-sounding. The column 'call' has two values, 1 and 0, indicating whether the resume received a call from employers or not. (Note that the 'b' and 'w' values in race are assigned randomly to the resumes when presented to the employer.)

Conclusion:
Racial discrimination is common throughout the world. Researchers performed a study to determine if there was a difference between black and white sounding names for callbacks of job applications in the United States. After analysis on this data set it appears that race has a significant role on call backs. The results from the survey show that white-sounding names received a callback rate of 9.65%, while black-sounding names received a callback rate of only 6.45%. This means that for every callback a black sounding name received, a white sounding name received 1.5 callbacks. We performed a few tests to see if this difference could be perceived as random using a 2 sample t-test and frequentist bootstrapping. The p-value for the t-test and bootstrapping are both low so we can reject the null hypothesis. This would mean white and black-sounding names do not receive the same callback rate showing that race could have a significant impact on the call back rate. There are however other variables (education, previous number of jobs, experience level, gaps in employment history, etc.) in the study that should also be taken into consideration in further examination.

Further Analysis:
White or black racial sounding names were a factor for callbacks in this study. It does not however mean it is the most important factor in callback success. We would need to amend the analysis to study the rest of the data to see what else may have had an influence.
