# MS POWER BI data academy project
Second project for obtaining certification and graduation from the Engeto IT School Data Academy.<br /> 
Discord name: marcel.suf

## Project Assignment
This time you will not be answering questions, but it is entirely up to you to choose which indicators are most interesting to you.
You can, of course, take inspiration from the questions from the first project, but most importantly you must graphically display them in a suitable way in the Power BI report.

Your task is to visualize your chosen dataset according to the criteria below.

**Criteria**<br /> 
The final PBI must meet the following criteria:<br /> 
1) 2-3 pages in length
2) Use of at least 5 different types of visuals
3) Filtering using slicers
4) Use of bookmarks/page navigation
5) Linking multiple data sources, either in Power Query or in Power BI
6) Use of a data hierarchy of at least two levels
7) Creating at least 1 measure (metric/measure) and 1 calculated column
8) Graphical editing of the visuals used and a visually friendly resulting report

## Description of the project
#### Data and import
Open data from the EU statistical office EUROSTAT on the development of net electricity production in Europe for the period 2017 - 2023 for both EU and non-EU countries was selected and obtained. Furthermore, data on population trends over several decades was obtained in order to convert the data per capita. For this, in the model, the conversion of electricity production per 1 million inhabitants was chosen. All data was directly linked to the data model in Power BI. Thus, data updates can be made in case of changes.
The data was modified and linked for display and assignment requirements. In addition, dictionaries with geolocation and dictionaries with names of individual electricity generation sources were linked to the main data.<br /> 
#### Project design
Furthermore, 3 main display pages and one Home Page were created according to the project specifications.
The first page contains an overview of electricity production trends for all countries with the possibility of filtering individual periods, sources of electricity production, etc.
The second page then allows the user to explore the selected country in detail for the selected period and further filter also the sources of electricity.
On the third page there are overview maps for both EU and NON-EU countries, which can be filtered or only selected countries can be viewed. These are summaries of total net production as well as per 1 million inhabitants.

### Datasets used:
**Net electricity generation by type of fuel - monthly data**<br /> 
https://ec.europa.eu/eurostat/databrowser/view/nrg_cb_pem__custom_9707004/default/table?lang=en <br /> 
*Explanatory text: https://ec.europa.eu/eurostat/cache/metadata/en/nrg_quant_esms.htm*<br /> 

**Population on 1 January by age and sex**<br /> 
https://ec.europa.eu/eurostat/databrowser/view/demo_pjan__custom_9757433/default/table?lang=en <br /> 
*Explanatory text: https://ec.europa.eu/eurostat/cache/metadata/en/demo_pop_esms.htm*<br /> 

**Vocabulary: Energy balance**<br /> 
https://dd.eionet.europa.eu/vocabulary/eurostat/nrg_bal/view <br /> 

**Vocabulary: Geopolitical entity**<br /> 
https://dd.eionet.europa.eu/vocabulary/eurostat/geo/view <br /> 


