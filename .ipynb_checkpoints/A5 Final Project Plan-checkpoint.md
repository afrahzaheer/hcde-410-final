# Overview and research questions
## Motivation and Problem Statement

Gun violence is a major issue in the United States, especially with the number of shootings and incidents that happen at schools. This project aims to dive into the data from 2024 to identify patterns related to gun violence, focusing on mass shootings and school-related incidents where people were either killed or injured. I think understanding these trends is crucial for figuring out where and how safety measures can be improved. By focusing on the frequency, timing, and locations of mass shootings, including those in schools, this project could offer insights that are relevant to policymakers, educators, and community leaders who want to help reduce violence. The findings might help target resources and safety efforts more effectively, especially in areas where people are more at risk. I hope to learn and better understand the patterns and factors behind gun violence incidents in 2024, with an ultimate goal of identifying potential areas for prevention.

## Data Selected for Analysis

This project will use two datasets from the Gun Violence Archive:
- 2024 Mass Shootings Dataset: This dataset includes reported mass shooting incidents in the U.S. up through November 10, 2024. It includes details like dates, locations, and number of victims and suspects killed or injured.

https://www.gunviolencearchive.org/reports/mass-shooting

- School Incidents Dataset: This dataset includes gun-related incidents at school campuses in the U.S. For this analysis, I’ll focus on data from 2024 and incidents where at least one person was injured or killed.

https://www.gunviolencearchive.org/school-shootings

These datasets are relevant, directly aligning with my goal to analyze current patterns in gun violence. Analyzing them can help identify key trends and risk factors, and using data from both mass shootings and school incidents could lead to a better understanding of gun violence in different contexts.

## Terms of Use
The data from the Gun Violence Archive is publically available, but the website states how they ask to be credited if their data is used.

## Ethical Considerations
Because of the sensitive nature of the data, I will focus my project on identifying broader patterns rather than going deep into specific individual cases. My aim is to get insights that can help improve safety while still respecting privacy.

## Unknowns and Dependencies
The datasets rely on reported incidents, so incidents from late 2024 may not be fully recorded. Also, there is definitely a possibility of some incidents not being recorded, which could affect the analysis. Also, some school shootings might also qualify as mass shootings, which could lead to overlap, so I need to remember to handle this overlap to avoid double counting.

## Research Questions
1. How frequently do mass shootings occur in the U.S. in 2024, and what are the key patterns in their timing and location?
2. What percentage of school-related shooting incidents also meet the criteria for mass shootings?
3. Are there trends in the number of fatalities or injuries based on location, time of year, or other factors?
4. How do the characteristics of school shootings differ from general mass shootings in terms of number of victims, location, and timing?

# Background and Related Work
Gun violence is a critical public safety issue in the United States, with mass shootings and school-related incidents occurring consistently every year. According to data from the Johns Hopkins Center for Gun Violence Solutions, firearm-related deaths reached record levels in recent years, with gun violence being one of the leading causes of death among children and teens in the country. The report highlights the urgent need for effective interventions to address the root causes of firearm violence.

Further emphasizing this issue, a recent analysis by the Pew Research Center found that the U.S. experiences significantly higher rates of gun-related deaths compared to other developed countries. The report indicates that while mass shootings make up a small fraction of overall gun deaths, they have a profound impact on public perception and policy debates.

These findings informed the focus of this project on analyzing mass shootings and school-related incidents in 2024. By examining factors like timing, location, and casualty rates, this study aims to uncover trends that could guide more effective safety measures and targeted prevention strategies. The goal is to provide data-driven insights that can potentially help shape policies that reduce gun violence occurrences.

Sources:

https://publichealth.jhu.edu/center-for-gun-violence-solutions/annual-firearm-violence-data

https://www.pewresearch.org/short-reads/2023/04/26/what-the-data-says-about-gun-deaths-in-the-u-s/

# Methodology
## Data Cleaning
- I will import the datasets from the Gun Violence Archive, and filter the data to include only incidents from 2024, focusing on cases where there were injuries or deaths.
- I will handle entries that are considered both mass shootings and school shootings, to make sure I don't count doubles
  
## Analytical Methods
**Descriptive Analysis**: I will start by summarizing the data using descriptive statistics, such as total counts of incidents, average casualties per incident, and breakdowns by incident type 

**Time Series Analysis**: I plan to analyze trends over time using techniques like moving averages to identify patterns in the frequency of incidents on a monthly or weekly basis.

**Geospatial Analysis**: I will analyze the geographical distribution of incidents using geospatial mapping to pinpoint regions with higher concentrations of violence.

**Comparative Analysis**: I will compare characteristics of school shootings with general mass shootings, analyzing differences in casualty rates, locations, and timing.

## Presentation of Findings

**Bar Charts and Histograms**: These will visualize counts and distributions, such as the number of incidents by month or the distribution of casualties.

**Time Series Plots**: Line charts will display trends in incidents over time, helping to identify peaks in violence during specific months or seasons.

**Geospatial Heatmaps**: I will use maps to show concentrations of incidents in different states or cities, highlighting areas with higher rates of gun violence.

**Tables and Summaries**: For comparative analysis, I will use tables to present differences in statistics between mass shootings and school shootings, making it easier to spot distinctions.

## Justification for Methods
My plan to use descriptive, temporal, and spatial analyses fits well with the nature of the datasets, which include categorical, temporal, and geographical variables. Using the specific data visualization  methods will enhance understanding of the results, making it easier to communicate patterns and insights to stakeholders.
