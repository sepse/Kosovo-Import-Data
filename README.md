# Kosovo Import Data :moneybag:  :bar_chart: 	:closed_book: 
A data science research project, analyzing import data from 2022 in Kosovo.

## Introduction

Analyzing import data using data science methodologies can provide valuable insights and benefits in several ways:

- Identifying patterns and trends: By analyzing import data, data scientists can identify patterns and trends in the types of goods being imported, the countries of origin, and the values of goods over time. This information can help businesses and policymakers understand the dynamics of international trade, detect emerging market trends, and make informed decisions.

- Market research and competitiveness: allows businesses to gain a deeper understanding of the market landscape and identify potential opportunities. By examining the types of goods being imported and their values, businesses can assess the competitiveness of their own products or identify areas for improvement. This information can help in strategic planning, product development, and market positioning.

- Supply chain optimization: help optimize supply chain management by identifying inefficiencies, bottlenecks, and opportunities for improvement. By examining the countries of origin, businesses can assess the reliability of suppliers, evaluate the impact of geopolitical events, and make informed decisions regarding sourcing strategies and supplier diversification.

- Risk assessment and mitigation: can aid in risk assessment and mitigation by identifying potential risks associated with specific types of goods or countries of origin. By examining the value of goods and tax payments, businesses can assess potential financial risks, evaluate compliance with regulations, and take necessary measures to mitigate risks such as customs duties, tariffs, or non-compliance penalties.

- Policy formulation and trade negotiations: Governments and policymakers can utilize import data analysis to inform policy formulation, trade negotiations, and economic development strategies. By examining the country of origin and types of goods, policymakers can identify potential areas for domestic production growth, assess the impact of trade agreements, and evaluate the effectiveness of import/export regulations.

- Fraud detection and prevention: Import data analysis can help detect and prevent fraudulent activities such as under-reporting of values, misclassification of goods, or illegal importation. By applying data science techniques, anomalies and suspicious patterns can be identified, enabling customs authorities and businesses to take appropriate actions to prevent fraud.

Overall, analyzing import data through data science methodologies provides valuable insights for businesses, governments, and policymakers. It enhances decision-making, improves market understanding, and helps in optimizing supply chains, managing risks, and fostering economic growth.

## Objective



## Data


Kosovo Customs Import datasets can be accessed via this link [Complete Datasets](https://dogana.rks-gov.net/per-doganen/statistikat-dhe-arritjet/bilanci-tregtare-bazuar-ne-tarife/)

## Methodology

All data processing, exploration and visualization will be conducted using Python notebooks hosted in Google Colab (a free service available to all Google users). The material is available as a tool to further explore the topics and learn about noise pollution in particular, and data science in general. Notebooks will open in Colab, where you can see the research methodology performed on the dataset; notebooks also allow you to tweak them to further explore the data on you own.

The data science methodology involves the following:

-Data loading: Load the dataset into the Python notebook using a library like Pandas. The dataset contains import data for the year 2022, with colums such as: Month, Country of Origin, Value of Goods, Type of Goods, Tax Paid, Excise Tax, Weight.
-Data cleaning: Check for missing or duplicate values in the dataset and remove or impute them as necessary. Also, check for outliers in the data and remove them if they are not meaningful.
-Exploratory data analysis (EDA): Explore the dataset using visualization techniques to understand the patterns and relationships in the data. Plotting histograms, line plots, and scatterplots can help you identify patterns, correlations, and distributions in the data. Use visualizations to understand the distribution of renewable powerplants in the world, and explore the relative capacitites of regional production.
-Visualization: Use visualizations to present the results of the exploration, create interactive maps showing areas of interest, or provide visualizations that help users understand the patterns of imported goods from certain countries.

**The notebooks:** [Kosovo Import Data](https://github.com/sepse/Kosovo-Import-Data/blob/b5e847cac6f2c2b07eace28740cd7bbdef82c55f/exim_dogana_2022.ipynb)

## First Results

![mapimport](https://github.com/sepse/Kosovo-Import-Data/blob/bd43efb2a9910a27d041f86d6fd746595766640e/Graphics/mapimport.png)


![top5](https://github.com/sepse/Kosovo-Import-Data/blob/bd43efb2a9910a27d041f86d6fd746595766640e/Graphics/top5.png)


![4chart](https://github.com/sepse/Kosovo-Import-Data/blob/bd43efb2a9910a27d041f86d6fd746595766640e/Graphics/4chart.png)


***For more detailed view on this research, please open the Notebooks, where more granular information is available in the visual and statistical form.***
