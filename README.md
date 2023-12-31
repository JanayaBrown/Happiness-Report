# Happiness-Report
Analysis of World Happiness Index Report to see what really makes people happy. 


## Motivation
The World Happiness Index Report is a global survery on happiness that influence policy making decisions. The goal of this project was to see which factors influece happiness the most drastically so that policy-making efforts can be focus. 

## Data Sources
### World Happieness Index Data
#### Sourcing 
This is an external data set owned by the Sustainable Development Network. The data comes from the World Happiness Report, a yearly survey on global happiness that influences policy-making decisions, and thus is susceptible to some bias. Political influences may sway respondents to lie on survey. To mitigate some of this bias, the sample is “national representative” and actual score is analyzed other parties. Thus, the source is relatively 
trustworthy. Datasets for [2015 - 2019](https://www.kaggle.com/datasets/unsdsn/world-happiness?select=2019.csv), and [2005 - 2022](https://www.kaggle.com/datasets/usamabuttar/world-happiness-report-2005-present) datasets were used analysis. 

#### Collection 
This data is externally collected via voluntary surveys once a year from 2005 to the present day. The data used for 
this analysis is from 2005 to 2019.

#### Contents
The World Happiness Report (WHR) uses survey data from the Gallup World Poll. The scores in the WHR are based on answers to the Cantril ladder, which asks respondents to rate aspects of their lives on a scale of one to ten (ten being the best). Then, Gallup weights are applied to make the estimates for the happiness score. Further estimates are used to see how much economic production, social support, life expectancy, freedom, absence of 
corruption, and generosity contribute to the happiness score. The [2015 - 2019](https://www.kaggle.com/datasets/unsdsn/world-happiness?select=2019.csv) dataset contained overall happiness rank for that year, country/region, and scores for happiness, GDP per capita, social support, healthy life expectancyat birth, freedom to make choices, generosity, and precerptions of corruption,= columns. The [2005 - 2022](https://www.kaggle.com/datasets/usamabuttar/world-happiness-report-2005-present) dataset contains country name, regional indicator year, log of the GDP per capita, healthy life expectacy at birth, and scores for social support, freedom to make life choices, generosity, perceptions of corruption, positive affect, negative affect, and confidence in the national govenment. 


#### Limitations and Ethics
Due to the nature of the “national representative” sample, the data may have sample bias. The sample may reflect
the population in a way that does not represent marginalized groups. It may also have some exclusion bias
depending on which countries are included in the survey. For example, if many western European countries 
abstained from participating, an analysis over the whole of Europe may have inaccurate results. 
The data is also limited by the grain of results. Happiness may vary from city to city, but the data only looks at the 
entire country. 

### Country Code Data
This external dataset is owen by Jaunu and contations countries ISO codes. The collection method is unclear. The columns included are the English name, the aplha-2 code, 
alpha-3 code,numeric code, and ISo 3166-2 for every coutry. The countries listed are only those recognized by the United Nations, and thus does not recognize locally or histoically significant boarders. The dataset can be abtained [here](https://www.kaggle.com/datasets/juanumusic/countries-iso-codes).

### Country GeoJSON Data
The external dataset was collection from Natural Earth and contaions vetor maps of every country present-day country in the world. The site used to abtaion the data can be found [here](https://geojson-maps.ash.ms/).


## Questions 
- How has happiness changed over time?
- Who are the happiest and least happy countries?
- What factors havet he grestest influence on happiness?

## Results and Visualizations
The storyboard for this analysis can be found on [Tableau](https://public.tableau.com/views/WorldHappinessIndexAnalysis_16868004411170/WorldHappinessIndexReportAnalysis?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link). Please note that the storyboard only contain the parts of the analysis that are the most germane to the final results. The code for the compelte analysis can be found "Scripts" folder. 
