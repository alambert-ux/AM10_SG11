# "No Need to Panic, It's All Under Control..." 
## A Visual Critique of European Government's COVID-19 Response Strategies

**Data Visualisation and Story Telling Final Group Project (Study Group 11)**

This study asks the exploratory question "What have European governments done to mitigate the spread of COVID-19?", before asking the more pressing follow-up: "How successful have these measures been at limiting cases and fatalities, and what be learned from both the greatest successes and failures?". 

Employing a breadth of visual and statistical techniques, including spatial mapping, time-series analysis, and linear regression, we compare the success of European governments in containing the fall-out from the global COVID-19 pandemic.   

Specifically, we seek to provide answers to the questions:   

**i.      WHERE have COVID-19 response strategies been successful?;**  

**ii.	    WHAT mitigation strategies have been most effective at combatting the virus?;**

**iii.	  WHICH factors are most important in determining the success of mitigation strategies and;**   

**iv.     HOW does the theorised efficacy of mitigation strategies vary between countries?**     

We conclude that, though the efficacy of certain measures is highly domain-specific, **stringent**, **stable** and **rapidly enacted (fast)** measures clearly predict how well national governments handled the crisis, providing valuable lessons for governments as they battle the second and third waves of the pandemic and seek to overcome pandemics in future.   

### Datasets

*We employ 3 datasets in our analyses, each of which we cleaned individually, before combining them into a single data frame filtered only to European cases, covid_europe*

Big dataset -> owid-covid-data   
https://covid.ourworldindata.org/data/owid-covid-data.csv

hospital data-> data  
https://www.ecdc.europa.eu/en/publications-data/download-data-hospital-and-icu-admission-rates-and-current-occupancy-covid-19

testing data -> covid-testing-all-observations  
https://github.com/owid/covid-19-data/blob/master/public/data/testing/covid-testing-all-observations.csv

the last one you need to open. then right click and choose save as csv

### Evaluating European Governments' COVID-19 Response Strategies

**OBJECTIVE 1** **Plots 1 & 2** Visualise the Current State of the COVID-19 Pandemic in Europe  

*Outcomes:*                     Two Spatial Maps, Demonstrating Current Normalised Cases and Deaths Across Europe  
*Insights:*                     An understanding of how different European regions have experienced the crisis differently, allowing selection of key cases    

**OBJECTIVE 2** **Plots 3 & 4** Compare How Key European Countries Have Experienced the Pandemic in Terms of Cases and Deaths, and the Measures they Have Taken  

*Outcomes:*                     Time Series Analyses Illustrating the Relationship between Stringency of Government Measures and subsequent cases/deaths  
*Insights:*                     Identification of countries where response strategies did & did not **i) Function as Expected**, and selection of interesting cases  

**OBJECTIVE 3** **Plot 5**      Deep-Dive into Specific, Characteristically Distinct Government Responses to the Pandemic   

*Outcomes:*                     Time Series Analyses Illustrating the Relationship between Cases, Tests, and Government Measures for Selected Cases from Plot 3  
*Insights:*                     Deeper understanding of the type of policies underlying the stringency index, and their relative **ii) efficacy** and timing  


**OBJECTIVE 4** **Plot 6**      Understand the empirical relationship between certain factors and COVID-19 cases to make prescriptive recommendations  

*Outcomes:*                     Ordinary Least Squares (OLS) Linear Regression Model Which Provides Both Factor Coefficient Estimates and Ranks Factor Importance   
*Insights:*                     Empirical relationships between government stringency (response) and outcomes, demonstrating: **iii) which factors are most                                         important in determining success of mitigation strategies** and **iv) how the predicted efficacy of mitigation strategies vary                                        between countries**
                                
                           
