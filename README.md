# Cost-of-Inequality-Socioeconomic-Status-12-Countries
This is a repository of the key visualizations and tech tools I used in the Cost of Inequality: Socioeconomic Status of 12 countries. In addition, the key data insights that I gleaned from analyzing the connection between socioeconomic status and different health outcomes.

## Project Description and Objective 

I am working with the World Health Organization to help them improve healthcare outcomes around the world. Per the World Health Organization website, this is a United Nations agency that connects nations, partners, and people to promote health, keep the world safe, and serve the vulnerable - so people can attain the highest level of health. The purpose of this organization is to lead global efforts to expand universal health coverage, direct and coordinate the world’s response to health emergencies, and promote healthier lives for all humans. 
The World Health Organization wants to see how socioeconomic factors impact healthcare outcomes. For this project we will focus on, 12 countries of different income levels to study trends between socioeconomic factors and healthcare outcomes.

The purpose of this project is to analyze 12 different countries' health outcomes and socioeconomic factors to explore connections between health outcomes and socioeconomic status. This project includes the years of 1992-2022. (i.e. How do income levels affect mortality rates?) The countries included in this project are split into different income levels: 3 high-income countries, three low-income countries, three lower-middle-income countries, and three upper-middle-income countries. The following countries are included in this project. 
**High Income:** Canada, United States of America, and France
**Low Income:** Mali and Afghanistan
**Lower middle income:** Ghana, Congo, India, and Nigeria
**Upper middle income:** Dominican Republic, South Africa, and Colombia

## Tools and Tech used in this project 

1. Excel: Used to pull the data from the World Bank Organization site. 
2. SQL: Used Basic to Intermediate Queries in this project. SELECT, FROM, Multiple Where Conditions, Aggregations, Case Logic, and Group By
3. Tableau: Used to create the data visualizations and charts comparing different healthcare outcomes with socioeconomic factors. 
4. Chat GPT: For prepping SQL queries and assisting in coming up with new queries to use.


## My SMART Questions and Pre-Analysis Initial Predicitons  

1.	How has college enrollment affected obesity rates across countries from 1992 to 2022? 
a.	Prediction: I would say there’s little to no correlation between college enrollment and obesity rates. I don’t think college education enrollment affects people’s diet that much. 
2.	How has mortality rates differed across countries based on income levels from 1992 to 2022?
a.	Prediction: I believe there’s a strong negative correlation between income levels and mortality rates. So, for instance, the lower-income nations, such as Mali, Nigeria, and Afghanistan, would have the highest mortality rates. Whereas the higher-income nations like France, Canada, and the United States of America would have the lowest mortality rates. 
3.	Is there a correlation between life expectancy and health expenditure across countries from 1992 to 2022?
a.	Prediction: I believe there’s a moderate positive correlation between health expenditure and life expectancy. To me, if you are spending more money on healthcare, then you are likely to have higher-quality healthcare services. However, not all of the high-income nations have universal healthcare systems where everyone can access healthcare. There are many nations like the USA, unfortunately that don’t have universal healthcare so the poor people are less likely to have quality health services which can negatively impact their life expectancy. I also believe that if you are spending less money on healthcare services, then there will be a lower life expectancy. 
4.	How have unemployment rates impacted suicide mortality rates and raised blood pressure rates in 1992 to 2002 as compared to 2012-2022?
a.	Prediction: I could see there being a strong positive correlation between unemployment rates and blood pressure rates. Like not having a reliable sense of income and lacking a sense of stability in life can lead to more stress. When there’s more stress there will inevitably be adverse health outcomes. With suicide mortality rates, I am not sure maybe a significant positive correlation. I think a person not having a job can really affected their self-esteem and self-worth. In extreme cases, when this person doesn’t have anything outside of their work identity they could choose instead to take their life. Perhaps, there could be factors outside of one’s employment or lack thereof that can lead someone to take their life. It’s also possible that someone could be extremely unhappy or stressed by their job and then choose to take their life. I am not sure about this one but I am very interested in exploring these correlations. I think in 2012-2022 there were higher unemployment rates than in 1992-2002. This is due to factors of just exiting the recession and people still struggling to find work and the pandemic of 2020 which negatively impact employment across industries. So I think with the higher unemployment rates there’s a slight possible chance that there are higher mortality rates and blood pressure rates. 
5.	How did the impact of college enrollment on HIV/AIDs incidence rates shift between 2005-2012 as compared to 2013-2020 across income groups?
a.	Prediction: I believe there is a strong negative correlation between HIV/AIDs prevalence rates and college enrollment rates. First, to be enrolled in college means you do have to be able to afford it (especially at a four-year university). If you did well academically or you performed well as an athlete, it’s possible to get financial aid that can aid with the cost. Overall, though I do feel that being at least middle class can significantly impact your chances of going to college. I also believe that the more educated you are, the more likely you are to do your homework on HIV/AIDs prevalence and take steps to protect yourself from it. Looking at 2005 to 2012 versus 2013-2022, I do believe that in 2013-2022 we say lower HIV/AIDS prevalence rates due to more education overall about STDs. I do think we will see lower HIV/AIDS prevalence rates regardless of college enrollment in 2013-2022 than in 2005-2012. 
6.	How do a nation’s income levels correlate mortality rates and life expectancy rates from 1992 to 2022?
a.	Prediction: I believe that a nation’s income level is moderately positively correlated with life expectancy rates. With higher income, people in the nation as a whole are more likely to have access to healthcare services, which can extend their lifespan. However, even in high-income nations, there are a great number of people who are living in poverty. Compounded by the fact that if a country doesn’t have a universal healthcare system like the USA, unfortunately. Then, people in poverty are even more likely to struggle with getting healthcare access due to legitimately living in survival mode. Though in lower-income nations, the healthcare access might not be as high-quality even if you are a rich person in that country. That can negatively impact mortality rates and life expectancy rates. 
7.	How did the relationship between current health expenditure and HIV/AIDs prevalence differ between 2005-2013 and 2014-2022 across income-level groups?
a.	Prediction: I believe that in 2005-2013, since that’s when HIV/AIDS prevalence came into focus, and the harm behind having HIV/AIDs, there was more money spent on HIV/AIDS programs. Countries spent more money on HIV/AIDS programs to either inform people about it or to look into healing people living with those conditions. Though it’s more likely that higher-income countries have more programs informing the public about HIV/AIDS prevalence. That can be an advantage of high-income countries over lower-income countries. In 2014-2022, when it was more stabilized, I believe countries lowered the expenditure budget on HIV/AIDS programs. However, I still do think that the more health expenditure you have in a nation the less likely the citizens of that country are going to contract HIV and AIDs. 
8.	How do a nation’s income levels affect raised blood pressure rates and obesity rates from 1992 to 2022? 
a.	Prediction: I believe there is a slight negative correlation between a nation’s income levels and blood pressure rates. I think that living in a high-income nation may provide more access to healthcare and health resources, which could help lower blood pressure rates. On the flipside, though, there could be more access to unhealthy food in higher-income nations. That can also impact eating habits for the consumers. Though if you are in lower-income countries, you might have more stress from struggling to get by on a budget. That can lead to higher blood pressure rates. I believe there is a slight positive correlation between a nation’s income levels and obesity rates. I think in higher-income nations, you have more access to food, and especially the unhealthy types of foods (like carbs, sugars, wheat, etc.), and this can lead to higher obesity rates. In lower-income nations, you might not have as much food readily available to you and thus won’t have as much access to unhealthy food. I’ll admit I’m also a bit unsure of the link between a nation’s income levels and obesity rates. I am excited to see what the data reveals about the link between blood pressure rates and obesity rates based on income levels. 





 ## Data Preparation Stage: Dataset Information and Limitations 

**World Bank Dataset Integrity and Credibility** 

1. Quote from the World Bank website “We ensure that our data work and products are of the highest quality by using standards, methodologies, sources, definitions, and classifications that are internationally accepted.”
2. Furthermore, the World Bank organization utilizes the General Data Dissemination System (GDDS) and Data Quality Assessment Framework (DQAF). The GDDS framework assesses different national statistical systems and encourages countries to improve their statistical systems over time. This framework also aides in distributing statistical information to the participating countries.
3. Explanation of Dataset: This dataset explores health data from several different countries from (1962-2022). This dataset utilizes a combo of healthcare factors and socioeconomic factors as indicators. Some of the healthcare indicators included in this dataset are mortality rates, HIV Incidence rates, overweight and underweight prevalence, and raised blood pressure rates. Some of the socioeconomic factors included in this dataset are current healthcare expenditure, enrollment rate percentages, and population growth. This dataset utilizes a lower bound, estimate, and upper bound as measurements of the indicators. Overall, this dataset looks at different global health and population trends from several different countries. This dataset includes different datasets with factors including reproductive health, nutrition, education, immunization, and diseases from over 200 countries.

**Dataset Limitations** 

1. Late enrollment, early enrollment, and repetition can lead to college enrollment rates being above 100%
2. Health Expenditure Data: 2000-2019
3. BP Data: No raised BP data beyond 2019
4. Nigeria only has reported college enrollment data for 2005,2010, and 2011
5. Canada and France are excluded from HIV Incidence rates questions

## Excel Results of Each of the Questions 










### Here's my visualizations for The Cost of Inequality: Connection between socioeconomic status and healthcare outcomes for 12 countries.

**Country Identifier Legend for the HIV Incidence Rates, health expenditure %, and income levels**
![Country Code Identifier as Country Names](https://github.com/user-attachments/assets/6c9bce1a-5185-4b37-a63d-88312ec83d7a)


![Obesity Rates and College Enrollment Rates ](https://github.com/user-attachments/assets/fe8864e7-84c3-4439-bfea-7587a59e9987) 

1. Positive correlation obesity rates and enrollment rates
2. Outlier: South Africa relatively high obesity rate at 23.63% and mid college enrollment at 20.48% which is sixth among countries.

![Mortality Rate by Income](https://github.com/user-attachments/assets/daf48b95-834a-421e-bc13-a5f2fb326615)

1. Strong negative correlation mortality rates and income levels
2. South Africa was the outlier as an upper middle income nation with a relatively high mortalilty rate at 121.1. Which is higher than lower middle income nations Ghana and India and a bit lower than Congo. 
![Life Expectancy and Health Expenditure % of GDP ](https://github.com/user-attachments/assets/f97248cb-f1e7-4b70-94a2-11365181032a)

1. Slight to moderate positive correlation health expenditure and life expectancy
2. Outlier: South Africa spent over 10% on health expenditure and low life expectancy of 61.44
3. Outlier: Afghanistan spent over 8% on health expenditure and low life expectancy of 60.25
![1992-2002 and 2012-2022 Unemployment Rate, BP Rate and Suicide Mortality Rate](https://github.com/user-attachments/assets/be112836-b7b2-460d-af98-26b9c006eac2)

1. Slight positive correlation between unemployment rates and raised BP rates
2. Slight positive correaltion between unemployment rates and suicide mortality rates
3. UE rates slightly decreased in 2012-2022 from 1992-2002 for most countries
4. Canada and France saw notable decreases in raised BP rates in 2012-2022 from 1992-2002 at 13.13% and 8%, respectively.
5. No significant change in suicide mortaity rates in 2012-2022 from 1992-2002 for most countries.
![2005-2012   2013-2020 HIV Incidence Rates, Enrollment Rates, and Income Levels](https://github.com/user-attachments/assets/91b2fa15-c2e7-41ac-ba86-b941d3b22427)

1. No correlation HIV Incidence rates and college enrollment rates or income levels
2. Outlier: South Africa significantly higher HIV Incidence rates at 9.92% in 2005-2012 and 6.41% in 2013-2020.
3. Positive correlation income levels and college enrollment rates
4. Slight negative correlation between HIV Incidence rates and income status in both 2005-2012 and 2013-2020
![Life Expectancy and Mortality Rates by Income](https://github.com/user-attachments/assets/748235d0-4a51-40c6-b5c2-8a420ee804df)

1. Moderate positive correlation between life expectancu and income levels
2. Outlier: South Africa there's life expectancy at 61.44 in the bottom three as an upper-middle income nation
3. I strongly suspect that South Africa having the highest HIV rates in the world per National Library of Medecine plays a significant role in the life expectancy.
4. No suprise here as income levels of a nation do a play a significant role in having higher quality healthcare services that can prevent premature deaths and extend the lifespan of individuals.
   
![2005-2013   2014-2020 HIV Incidence Rates, Health Expenditure %, and Income Levels](https://github.com/user-attachments/assets/c06fd068-515e-4f92-a6ed-2e8748439b8a)

1. Negative correlation health expenditure and HIV Incidence rates
2. Outlier: South Africa. Pretty consistent theme with the HIV Incidence correlations for sure. 
![1992-2022 Obesity Prevelance Rates and Raised BP Rates ](https://github.com/user-attachments/assets/3c3e60f3-1fd2-4509-8f8b-033d830cd6d0)

1. Slight negative correlation income levels and raised blood pressure rates
2. Outlier: Dominican Republic and South Africa
3. Dominican Republic had highest raised BP rate at 38.38% and fourth highest obesity rate at 18.71%
4. South Africa had the third highest raised BP rate at 34.18% and second highest obesity rate at 23.63%.
5. Positive correlation income levels and obesity rates
