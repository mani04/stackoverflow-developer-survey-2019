# Data Analysis: Who are the open source contributors?


## Platform Requirements

You will require the following tools and packages in your system:

1. Python 3.x (preferably 3.8+)
2. Jupyter Notebook
3. Pandas
4. Numpy

In addition to the above packages and tools, you will also need to download the 2019 developer survey results from Stackoverflow and place it in the following folder / filename: `data / 2019.csv`. The developer survey can be downloaded from [this link](https://insights.stackoverflow.com/survey).


## Project Motivation

This is an attempt to look at whether open source contributors are getting rewarded for all the hard work that they put in without any apparent rewards in a direct form. Stack Overflow survey in the year 2019 has data about open source contributions of developers, which could be used to make this analysis.

This project looks at the following data from stackoverflow developer survey:
1. Open source contribution frequency
2. Operating System that they use
3. Annual Compensation (Salary)
4. Career Satisfaction


## Methodology

This analysis primarily involves using cross tabulation of categorical variables. 3 of the variables are categorical. Salary is converted into categorical variable by splitting into quartiles to make this analysis possible.


## Acknowledgements

Data: Stackoverflow Developer Survey 2019


## Licensing

You are free to use the analysis in this repository without any restrictions.
