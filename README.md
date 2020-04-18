# Outsourcing Trends in Department of Health and Human Services
SCOPE

Motivation: Several team members work with the federal government and were interested in understanding trends about the work that the federal government outsources and whether there are noticeable differences over time, perhaps indicating differences between presidential administrations

Plan: Visualize federal government procurement data trends over time
Primary Data Source: USAspending.gov 

Advantages
Singular primary source of multi-year data across the whole federal government with 277 fields and a data dictionary

Primary challenge: Data Size
Massive files that we could not load onto GitHub
Mitigation – Focus on a subset of the data.  Investigated Department of Health and Human Services (HHS) 
Still too large but mitigated by reducing the dataset offline – removed ~200 fields
Still too large – so, split the file into 2 files per year and were able to upload them to GitHub
Ultimately created a single csv by reading in and merging 18 csv files (2 per year of data); this csv was read in by the individual team members to start their respective analyses and visualizations


Major Trends:
Over the period 2012-2019, HHS has outsourced $165B of products and services
HHS outsourcing has grown by 20% over 8 years, there’s no discernible difference in the trend between administrations
While contracts have been awarded to 45 foreign countries, more than 99% of contract dollars are attributable to US companies
Low competition can lead to the government paying higher prices for goods and services. Despite most HHS contracts being open for competition, the data shows that there are very few companies that are fighting for each contract.


