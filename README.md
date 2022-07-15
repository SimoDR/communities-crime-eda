# Exploratory Data Analysis - Communities and Crime over the US Population

In this report we perform a study of social aspects of the population of the United States of America, focusing on their influence over the number of violent crimes committed in every community. Various categories of features are considered, from the ethnic composition to the economic conditions of the different communities, from the level of education of people to the family background of children.

Through this paper we will analyze the dataset and its features, in order to find out which of them are more linked together and which ones have more influence over the total number of violent crimes. Several statistical tools will be used to train different regressors, in order to predict how many violent crimes will occur in a given community. Among the most relevant features we discovered that the family background plays a major role, making the rate of children with just one parent one of the most important factors, along with the average income of the population.

The second question aimed to find if there is a connection between the ethnic composition of communities and the number of violent crimes reported in that community: in particular we compared how the situation changes when the population is majority of African-american ethnicity, and Caucasian ethnicity. We discovered that the African-american ethnicity is associated with features that corresponds to a high level of crime, the opposite is true for the Caucasian ethnicity, and that by filtering out this "confounding" factors, the criminality rate is mostly independent from the ethnicity. This proved that the higher criminality rate that is reported in communities with a majority of African-american ethnicity is actually due to the worse socio-economic condition for the African-american population, with respect to people of Caucasian heritage.

At the end the focus will be on specific zones of the US territory, the ones with a peculiar presence of African-americans or people of Caucasian heritage.

## Files

In this repository, there are two files:

- `script_code.Rmd`: R Markdown notebook with the source code for the analysis;
- `report.pdf`: a report in which we summerize the analysis process and the statistical results.
