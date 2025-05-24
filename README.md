# Azure-Covid19-datafactory-project
Created a project based upon learnings and practice along with hands on experience of Azure Data Factory, azure portal and some use of other services of azure as well. It follows a structure of trying to load the covid19 data from the link for different countries which are defined on the basis of different country names.

The project is based around reporting and prediction of COVID-19 spread. Firstly, we want to create a data platform from which our data science team can run machine learning models to predict the spread of the virus, and find other insights from the data. Secondly, we wanna create a data platform from which our data analysts can easily report on the COVID-19 trends using a reporting tool. So, those are the two main objectives of our project. The solution that we are building will be limited to reporting on the data related to EU countries and UK only. 

The data lake that we build will be populated with details about the confirmed COVID-19 cases on a daily basis, the unfortunate mortalities as a result of COVID
on a daily basis, the hospital admissions, and ICU cases. We will have both new numbers per week as well as people in hospital at the end of the day, testing details such as tests being carried out per week, and any new COVID cases from the tests. And finally, we'll also get the statistics about the population in every country by age group. This data could then be used by our data scientists to predict the spread of the virus. Things like creating machine learning models will be outside the scope of this project.

Our main objective here is to create a data platform from which our data scientists can create machine learning models. We'll then populate the data warehouse with the subset
of the data so that it can be used for reporting on trends. The data warehouse will include details about confirmed cases, unfortunate mortality rates, hospitalization and ICU cases from our weekly counts in the data lake, as well as the testing numbers.

The solution we are building will be specific for European countries only. We'll use the European Center for Disease Prevention and Control website as the source for our confirmed cases, mortality, hospitalization cases, ICU cases, and testing numbers. And we'll use the Eurostat website for population by age data.
