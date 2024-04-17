# 🦠 Project Geospatial Anaylysis of Cancer 🦠

## Table of Contents

1. [Live Demo](#Live-Demo)
2. [Abstract](#Abstract)
3. [Problem Definition](#Problem-Definition)
4. [Methodological Approach & Implementation/Analysis](##Methodological-Approach-&-Implementation/Analysis)

## [Live Demo 🎥](https://drive.google.com/file/d/1ooAWBABH4AIo4H9gAo2G-1EiZZJw1oMP/view?usp=sharing)

## Abstract

Our project's focal point lies in the creation of dynamic dashboards, illuminating intricate patterns within lung and liver cancer incidence rates. 
These visualizations will encapsulate a rich tapestry of graphs, plots, and correlations, offering a comprehensive exploration of the interplay between gender, race, and various influencing factors. 
The goal is to provide an intuitive and interactive platform that not only displays the raw data but also unveils the complex relationships shaping cancer disparities. 
Through these dashboards, users can unravel the nuanced connections between lifestyle choices, environmental factors, and the prevalence of cancer. 
The visual narrative will transcend conventional data analysis, fostering a deeper understanding of the multifaceted aspects contributing to divergent cancer rates focusing on the areas of US states and counties.

## Problem Definition

Our datasets have undergone meticulous processing, laying the foundation for a nuanced exploration of cancer incidence. 
An initial foray into mapping cancer rates across US counties has provided a visual overview of their spatial distribution. 
This preliminary step enhances our comprehension of the geographic nuances surrounding cancer prevalence. As we delve into the specifics of lung and liver cancer, our preliminary research has illuminated key patterns. 
Notably, gender-based disparities in Hepatocellular carcinoma (liver and lung cancer) have surfaced, with men exhibiting rates often more than twice as high as women (American Cancer Society, 2019). 
These gender-centric insights align with established knowledge, setting the stage for a targeted investigation. 
We've identified lifestyle factors as pivotal influencers. Factors such as smoking's impact on lung cancer and binge drinking's association with liver cancer are foundational to our approach (Mayo Clinic, 2022)  (Mayo Clinic, 2023). 
This initial phase not only streamlines our analytical path but also positions us to dissect the intricate dynamics of cancer disparities with informed precision

## Methodological Approach & Implementation/Analysis 

In our methodological approach, we prioritize data accuracy and coherence by meticulously cleaning, wrangling, and merging datasets. 
Leveraging the powerful RMarkdown tool within RStudio, we create dynamic and interactive dashboards to enhance the user experience. Our statistical analyses involve regression studies, correlation assessments, and rankings, revealing intricate patterns within the data. 
Additionally, we employ geospatial mapping techniques to vividly illustrate state and county-level variations in cancer rates. 
The overarching objectives of our work are to facilitate a user-friendly exploration of liver and lung cancer disparities, unveil nuanced patterns across general, race/ethnicity, and gender dimensions, and establish a robust foundation for informed decision-making and further in-depth analysis.

### What specific hypotheses are we testing? 

- Geospatial Overview: 
  - Hypothesis: Mapping cancer incidence rates across the entire U.S., filtered by gender, race, or general parameters, would provide a visual overview, revealing regions with the highest rates and identifying states with missing data. Looking at the geospatial data, we hypothesize that there will be certain areas of high concentration of cancer rates, and that other regions will share low cancer rates.
  Counties will often be next to the other counties with similar cancer rates.
- Detailed Numeric Insights:
  - Hypothesis: Compiling detailed numeric figures related to cancer incidence rates and influential factors at the county level would present a challenge, especially when dealing with 10 relational tables. However, this detailed information could be effectively integrated into an interactive map for a more granular understanding.
- Top 5 and Bottom States/Counties:
  - Hypothesis: Exploring the top 5 and bottom states and counties with the highest cancer rates, as well as presenting average rates based on gender and race groups, would offer valuable insights into regional disparities. The team hypothesizes that a few top states will hold a majority of the top counties, and that the top states will be near each other geographically.
- Factor Influence on Cancer Rates:
  - Hypothesis: Investigating the influence of factors on cancer rates by dividing cancer rates into gender or race groups would be a challenge due to the general rate values of factors at the county level. The methodology involved showcasing correlations of these factors with cancer rates under gender or race through graphs. The team hypothesizes that the major factors supported by medical research will play the largest part in determining cancer rates, for instance binge drinking and liver cancer, smoking and lung cancer, diabetes and general cancer rates. The team also hypothesizes that the data should agree with medical sources on the differences in gender and race for cancer rates.
- Correlation Analysis:
  - Hypothesis: Examining the correlation between different factors, as well as the correlation of each factor with the rate of liver or lung cancer, would unveil complex relationships. Utilizing a U.S. map to visualize the overall influence of each factor on regions and exploring detailed figures for the top 5 states and counties affected by each factor further enriched the analysis. The team hypothesizes that maps that show density of factors correlated to cancer will correspond to density in the rate of cancer maps. The team also hypothesizes that there will be major interactions between factors, and that those interactions change the rate of cancer in certain counties. 

