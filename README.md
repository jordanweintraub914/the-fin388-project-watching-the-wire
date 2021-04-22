# Does the location you live in determine the allocation of how you spend your stimulus checks?
By Jordan Weintraub, Randy Parker, Leo Pawlika

## Research Question
Bigger Problem we are interested in:
- Can we confidently determine how someone will spend most of their stimulus checks based on certain descriptive statistics?
- What indicators effect how someone spends their stimulus funds? 

Specific research question we are trying to answer:
- Does the location someone lives in determine how they will spend their stimulus money?

Hypothesis: The state one resides in has an effect on what they spend most of their stimulus checks on.

Necessary metrics:
Performing Regression...
- A statistically significant beta coefficient and a strong correlation between the location the person resides in and the category (expensive, paying off debt, etc.) they spend most of their stimulus checks on.
- Adding in other predictor varaibles (disposable income, race, etc.) and comparing the results. 

## Necessary data:
What does the final dataset look like?
- Unit of observation: a household's #1 stimulus payment spending usage.
- Sample period: March 17th to March 29th, 2021 (week 27).
- Sample conditions: Person/household must have graduated high school, must be unemployed.   
- Necessary varaibles: location of each observation, number 1 spending category. 
- Favorable variables: the amount someone spends on each respective spending category (quantitative data as opposed to ordinal data).

Data we have and data we need:
- Should have all the necessary data we need from the United States Census Bureau Household Pulse Survey 
- Would help if we found another dataset that includes the proportion of how households spend their stimulus, instead of only having the number 1 spending category.

How to collect more data:
- Need to conduct more research on stimulus spending habits (Finding more public surveys).

Raw inputs and how we will store them:
- Create an inputs folder, download CSV file from the public housing survey and store the file in the inputs folder.

Transforming data to final form:
- Will need to perform EDA to ensure our dataset is cleaned (no outliers, data errors, etc.).
- Will need to group the dataset by its respective categories.



### Useful guidelines from Professor Bowen 
1. Reading [the tips on working with github again](https://ledatascifi.github.io/ledatascifi-2021/content/assignments/howto_do.html#working-on-assignments-projects-taking-notes) because these are especially important when working on team repos. 
2. Also, read the page on [team coding](https://ledatascifi.github.io/ledatascifi-2021/content/05/01c_teams.html)
3. Then decide as a team how you’ll work on stuff together. 
4. Read the instructions in total before you get going. They are in a subfolder here and also on the [website](https://ledatascifi.github.io/ledatascifi-2021/content/assignments/project.html). The website version might be easier to read. 
5. Review [Chapter 2](https://ledatascifi.github.io/ledatascifi-2021/content/02/10_Golden_1.html) of the textbook. It is all about tips to make building a project less painful, more productive, and more rewarding.
