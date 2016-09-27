# OpenSDG
Architecture for 4publishing [UN Sustainable Development Goals](http://www.un.org/sustainabledevelopment/sustainable-development-goals/) (SDG) [indicators](http://unstats.un.org/sdgs/indicators/database/) as Linked Open Data with the OpenCube Toolkit.

Coursework for *Architecture Design* at Delft Technical University. Not actively maintained.

## Mission and scope
Track progress on ending world hunger with linked open data and a visualization dashboard

## User scenario: National politician informing decision-making process
When deciding on national policies, a political representative wants a fact-based approach. She uses the application to compare the status of her country to that of a neighbouring country, and to the metrics set by the Sustainable Development Goals in general.

## Assessment of potential (linked) open data sources
Source | Data quality (ie, temporality, completeness) | Open data | Linked data
[World Food Programme](http://vam.wfp.org/sites/mvam_monitoring/) | Report | No | No
[Food and Agriculture Organization](http://faostat3.fao.org/download/D/FS/E) | Database | Yes | No
[World Bank](http://www.worldbank.org/) | Database | Yes | No


## Architecture challenges
*Scoping, system boundaries
*Trade-offs made
 *start with single SDG, must fit all SDGs
*Technical Challenges
 *Data Quality (Fragmented data, currently the data are in many locations and not linked)
 *Partially Open Data (ex: FAO & World Bank are open data while WFP in the form of report)
*Technology used
 *OpenCube Toolkit (Data Creation, Publication and Usage)
 *R Statistical Analysis Module (OpenCube extension) for Data Analysis and Dashboard


