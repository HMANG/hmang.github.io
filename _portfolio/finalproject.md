---
title: "Parks in Philadelphia"
excerpt: "About me"
author_profile: true
redirect_from: 
---
My project aims to explore the spatial distribution of urban parks in Philadelphia, PA in relation to variables such as race, income, and more. Prior GES courses have emphasized the importance of these spaces, which can address health inequality and contribute to sustainable urbanization by providing environmental, economic, and social benefits. The study by Alizadehtazi et al. titled "Urban Park Usage During the COVID-19 Pandemic" served as inspiration, highlighting the significance of parks during the pandemic. Ken Steif's analysis on equitable park accessibility in Philadelphia also guided the methodology of my study. 

Data and Methods
======
The park dataset was sourced from opendata.arcgis.com and opendataphilly.com, while census data was obtained from the American Census Survey using the tidycensus package in R-studio. The bulk of the analysis was conducted in R-Studio, and the resulting maps were finalized using QGIS. Two layouts were created in QGIS. The first layout examined the distribution of neighborhood parks in relation to the percentages of White and Black populations across census tracts. The second layout compared household income and property value.

Results and Analysis 
======
The analysis revealed no skewed distribution of parks throughout Philadelphia. However, larger parks tended to be located in census tracts with a majority of White residents. These parks also aligned with census tracts characterized by higher household income and property value. Map 1 depicted this association between park size and the racial composition of surrounding communities, while Map 2 illustrated the relationship between park size and socio-economic status. These patterns could suggest disparities in resource allocation and investment, potentially resulting in larger parks in more affluent areas. It also indicates differential access to green spaces, with wealthier communities benefiting from larger and potentially better-maintained parks. Such disparities can impact community well-being and various health and social benefits associated with access to nature and recreational areas.

Conclusion
======
The association between park size and socio-economic characteristics underscores the need for further research to explore underlying causes and consequences. Factors such as historical development patterns and community preferences should be considered in future investigations. The analysis should be interpreted cautiously, recognizing the limitations of spatial analysis in capturing the complexity of park size disparities.



