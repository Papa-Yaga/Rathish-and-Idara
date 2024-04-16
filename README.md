# Rathish-and-Idara
# Title of the project
#Exploring the Relationship between Economic Prosperity and National Hapiness
# Introduction to your project.
#Rationale: Economic prosperity often correlates with access to resources, healthcare, education,and overall well-being
#Therefore, countries with higher Gdp per capita may prioritize social welfare programs and have happier citizens.
# Data you are using (and comments, main challenges, strengths & weaknesses, etc…)
#We used the data from the World happiness report and exttracted the Gdp data using the World Bank Api.
#One of the challenges involved the extraction phase, the world bank has a different way of extracting the data, and we had to utilize those.
#Then, we had some challenges with cleaning and formatting the data, this was however resolved in no time.
# Questions you want to answer (maybe divided by different topics). Each question should include a conclusion written in a markdown cell.
#The main question we sought to answer was to check if there is a correlation between Gdp rates and happiness
#And we found a positive correlation between both.
# Describe the methodology you are using, explaining the steps you took for data cleaning, analysis, etc.
#we used a difference in difference methodology to check for consistency in our results
#the idea was to see if the covid 19 pandemic could potentially bias our results
#2019 was the control group data, and 2021 was the treatment group data.
#For the cleaning, we renamed columns, dropped columns and rows we considered irrelevant for our analysis, replaced certain values and converted the GDP to logarithm to facilitate better visualization and analysis

# Conclusions after your analysis.
#After the analysis, we find a positive correlation between gdp per capita and national happiness, and this remains consistent with our initial hypothesis.

# Links to data sources
#https://rathishdata.kanbantool.com/b/1049717#
#https://www.kaggle.com/search?q=world+happiness+report+2019
#https://www.kaggle.com/search?q=World+Happiness+Report+2021