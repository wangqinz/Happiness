# Description

You should have three datasets, `happiness_data.csv`, `happiness_valid.csv` and `CountryInfo.csv`.

## Happiness Data

The two datasets `happiness_data.csv` and `happiness_valid.csv` have the same predictors, but the response variable `Happiness` is only included in `happiness_data.csv`. The explanations for these variables are as follows.

| Variable | Unit | Description |
| -------- | ---- | ----------- |
| Population | Person | Population data from United Nations |
| GDP | Billion $ | Gross Domestic Product from United Nations |
| Support |  | National average of the binary responses (either 0 or 1) to question (Q1) |
| Health | Year | Healthy life expectancies at birth |
| Freedom | | National average of responses to question (Q2) |
| Generosity | | The residual of regressing national average of response to question (Q3) on GDP per capita |
| Corruption | | The national average of the survey responses to two questions (Q4) |
| Positive | | The average of three positive affect measures: happiness, laugh and enjoyment (Q5) |
| Negative | | The average of three negative affect measures: worry, sadness and anger (Q6) |
| Government | | Confidence in the government |
| Gini Index | | The Gini Index of household income |
| Happiness | | The national average response to the question of life evaluations (Q7) |
 
### Questions

#### Q1
  - If you were in trouble, do you have relatives or friends you can count on to help you whenever you need them, or not?
  
#### Q2
  - Are you satisfied or dissatisfied with your freedom to choose what you do with your life?
  
#### Q3
  - Have you donated money to a charity in the past month?
  
#### Q4 
  - Is corruption widespread throughout the government or not?
  - Is corruption widespread within businesses or not?
  
#### Q5
  - Did you experience the following feelings during A LOT OF THE DAY yesterday? How about Happiness?
  - Did you smile or laugh a lot yesterday?
  - Did you experience the following feelings during A LOT OF THE DAY yesterday? How about Enjoyment?
  
#### Q6
  - Did you experience the following feelings during A LOT OF THE DAY yesterday? How about Worry?
  - Did you experience the following feelings during A LOT OF THE DAY yesterday? How about Sadness?
  - Did you experience the following feelings during A LOT OF THE DAY yesterday? How about Anger?
  
#### Q7
  - Please imagine a ladder, with steps numbered from 0 at the bottom to 10 at the top. The top of the ladder represents the best possible life for you and the bottom of the ladder represents the worst possible life for you. On which step of the ladder would you say you personally feel you stand at this time?
  

## Country Information

| Variable | Description |
| -------- | ----------- |
| Country/Territory | The name of countries or territories |
| Code | The three digit codes of countries or territories |
| Region | The region each country or territory lies in, as defined by United Nations |

_You can assume that the Country/Territory column in all three tables match each other._