# Crime Economics and Proposition 47

## Introduction
Among complex societal challenges, crime stands as a persistent and multifaceted issue that affects communities worldwide. While it is widely acknowledged that crime is influenced by a myriad of factors, the interplay between education, economic conditions, and geographic location remains a critical area of inquiry. Education is often posited as a tool for social mobility and a deterrent against criminal behavior. Simultaneously, economic factors such as income inequality have been correlated with crime in various studies, suggesting that economic health is a significant predictor of criminal activity. As urban, suburban, and rural areas each present distinct socio-economic profiles, the location of districts may also contribute to differences in crime rates.
 
Besides intrinsic characteristics of regions, external factors such as policies stipulated regarding judicial enforcement and penalties for crimes would also influence crime rates. For instance, Proposition 47 legislated in 2014, California primarily reduced some nonviolent crimes from felonies to misdemeanors, making store theft under $950, forgery, receipt of stolen property, and even certain drug possession crimes a "misdemeanor," punishable by no more than 12 months in prison. Some are concerned that the bill could lead to the early release of offenders deemed to pose a low risk to society, who could re-offend and threaten public safety. Thus, Proposition 47 is seen as detrimental to social order and potentially increasing the crime rate, serving as great example to examine the effects of public policy on crime rate.

## Research Method
This paper aims to explore how the location, education level, and economic development of the region would contribute to the crime rate across the nation in the post-pandemic era, particularly in the interest of investigating whether, due to the implementation of Proposition 47, certain regions in California reveal a statistically significant trend of crime rate from rest of the nation. This paper adopts data published by LAPD, cleaned data using data science techniques, and clustered data with machine learning methods such as K-means. Through multivariate linear regression analysis, this paper wishes to see to what extent the difference in crime rate could be attributed to the factors listed above. Additionally, this paper uses logistic regression to predict the probability of crimes being conducted with known influencing factors. It also adopts ARIMA to detect potential seasonality in the variation of crime data. 

This paper hypothesized that all locational, economic, and educational factors possess a positive causal relationship with the crime rate, and counties in California present more rapid growth of criminal rate compared to other states due to the formulation of Proposition 47.


