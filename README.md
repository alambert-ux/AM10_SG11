# "Don't Panic, It's All Under Control..." - A Visual Critique of European Government's COVID-19 Response Strategies
*Data Visualisation and Story Telling Final Group Project (Study Group 11)*

This study asks the exploratory question "What have European governments done to mitigate the spread of COVID-19?", before asking the more pressing follow-up: "How successful have these measures been at limiting cases and fatalities, and what be learned from both the greatest successes and failures?"

Employing a breadth of visual and statistical techniques, including spatial mapping, time-series analysis, and linear regression, we compare the success of European governments in containing the fall-out from the global COVID-19 pandemic, and draw conclusions including i) which countries' strategies functioned as expected; ii) for a set of distinct cases, what mitigation strategies seem most effective in combatting the virus; and, most fascinatingly, iii) how, though the efficacy of certain measures is highly domain-specific, stringent, hard and fast measures almost exclusively predict how well national governments handled the crisis.

## Datasets

*We employ 3 datasets in our analyses, each of which we cleaned individually, before combining them into a single data frame filtered only to European cases, covid_europe*

Big dataset -> owid-covid-data
https://covid.ourworldindata.org/data/owid-covid-data.csv

hospital data-> data
https://www.ecdc.europa.eu/en/publications-data/download-data-hospital-and-icu-admission-rates-and-current-occupancy-covid-19

testing data -> covid-testing-all-observations
https://github.com/owid/covid-19-data/blob/master/public/data/testing/covid-testing-all-observations.csv

the last one you need to open. then right click and choose save as csv

**The Worldwide Development of the COVID-19 Pandemic**

*OBJECTIVE 1*     Visualise the Spread of the Virus in Terms of Mortality
Outcomes:       time series + mapping (geospatial visualisation)

*OBJECTIVE 2*     Geographic Heterogeneity in the Virus in Terms of Mortality
Outcomes:       static maps + regional heterogeneity (e.g. showing death/infection rate by age, across geographies)

*OBJECTIVE 3*     Mortality Outcomes in key regions/geographies (the temporal evolution of the virus)
Outcomes:       time series with specific national policy events

**Visualisation Ideas / Checklist**

1. Time Series Plot
2. Parallel Sets Plot
3. Mapping (static and interactive / dynamic / time series)


        
