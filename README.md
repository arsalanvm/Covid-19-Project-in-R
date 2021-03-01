# Population density and death rate prediction of Covid-19

Over the past several months, the world has experienced much turmoil due to the novel coronavirus, Covid-19.
Many researchers are trying to understand the primary reasons for the spread of this virus. When the virus
first appeared in the United States, many large cities, such as Seattle and New York, experienced major
outbreaks as the virus spread very quickly. Later, a similar phenomenon occurred in Miami, New Orleans, and
Chicago. States with a very high population density, such as New Jersey, Connecticut, and Massachusetts, also
had spikes in the number of cases. It is very likely that high population density may be a cause for the high
number of coronavirus cases due to the close proximity of people in these locations.

Medical professionals have also stated that people may have contracted the coronavirus while still being
asymptomatic, i.e. they do not show symptoms. It is likely that people who are in a good state of health have
an immune system that is able to fight off the virus while experiencing mild or no symptoms. However, those
people who are at high risk for infection or have severe comorbidities may experience very severe symptoms of
the virus, such as respiratory problems, high fever, muscle or body aches, or persistent chest pain. When the
virus first appeared in the US, the shortage of testing capacity led to only those people who showed symptoms
being tested for the virus. It is possible that the presence of comorbidities and those at risk for illness due to
Covid-19 may be a cause for a higher number of cases.

The purpose of this project is to investigate whether differences in population density, number of cases of
Covid-19, and population of select age groups among states is causing a higher number of deaths due Covid-19
in each state, respectively. We plan to investigate this by using state-specific data and building several linear
regression models. We have the total number of Covid-19 deaths by state, the population, population density
and population of different age groups for each of the 50 states and the District of Columbia as of 2018. To
investigate whether a higher population density, number of positive cases, and age groups are causing a higher
number of Covid-19 deaths, we will build a regression model that predicts the the death rate based on these
variables.

Other variables, such as state-ordered facemask mandates, state-of-emergency declarations, percentage of
people over 65, and percentage of the population living in poverty, will also be considered as covariates that
could further explain the causes for the number of cases by state.


requirements:

- R Studio

- readxl

- stargazer

- lmtest

- sandwich 

- ggplot
 
