
![map1](/maps/map1_afg_conflict_events_post.png)

# Map 1: Afghanistan conflict locations | 1st Nov 2021

<br />

**#30DayMapChallenge theme:** points <br />
<br />

### Data

- Armed Conflict Location and Event Data – ACLED (Raleigh et al., 2010; [https://acleddata.com/](https://acleddata.com/)) <br />
- GADM administrative boundaries (Global Administrative Areas, 2020; [https://gadm.org/data.html](https://gadm.org/data.html)) <br />
<br />

### Code

Available here: [https://github.com/cadooley/map_challenge_2021/blob/main/RScripts/map1_afg_conflict_events.R](https://github.com/cadooley/map_challenge_2021/blob/main/RScripts/map1_afg_conflict_events.R) <br />
<br />
I used the *sf* (Pebesma, 2018) and *data.tables* (Dowle et al., 2021) packages to convert data into an easy-to-use format, and the *viridis* package (Garnier et al., 2021) for the colorblind-friendly colour palette called ‘mako’. <br />
<br />

### About the map

Afghanistan has experienced decades of armed conflict ([see this NPR article for a tiemline of events](https://www.npr.org/2021/08/19/1028472005/afghanistan-conflict-timeline?t=1635582485925)). The true number of conflict related fatalities is unknown, however, many organisations and researchers have produced estimates for different time periods and particular wars. Estimates of fatalities since 2001 (the beginning of the US-led invasion) mostly vary between approximately 150,000 and 200,000 deaths, depending on the source.
While estimating the number of deaths nationally is important for quantifing overall impacts of war, subnational estimates provide information about the severity of conflict in different regions and can be crucial for identifying the most vulnerable subpopulations. 
<br />
<br />
The ACLED database provides a transparent collation of evidence of conflict events across the globe. The ACLED team have standardized the information extracted from news reports and other sources, which includes the type of event (e.g. battles, riots, explosions, etc.), actors involved, date and location. ACLED provide an impressive level of transparency about their approaches through [videos and guides](https://acleddata.com/resources/general-guides/), including a comprehensive [codebook](https://acleddata.com/acleddatanew/wp-content/uploads/dlm_uploads/2019/01/ACLED_Codebook_2019FINAL.docx.pdf) explaining all the variables, values and categorizations in their datasets. One key feature of this database is the geo-referencing of events which allows affected populations to be pin-pointed. Because exact geo-locations are not always available, ACLED include precision scores for each event’s coordinates (1 = high precision, e.g. the settlement name or coordinates were reported; 2 = the part of the region was reported; 3 = only a large area or region name was reported). Similarly, precision scores are provided for dates of events too. This information means that practitioners and researchers can consider and evaluate uncertainties around which subpopulations may have been affected by conflict, informing response actions and delivery of services.<br />
<br />
The map above illustrates a subset of ACLED's data, showing the cumulative number of fatalities at each reported armed conflict location in Afghanistan between January and mid-October 2021. The ACLED data documents a total number of 41,689 fatalities across 9,077 conflict events at 712 locations, during this time period. <br />
<br />
Afghanistan, like many other countries, faces a multitude of interacting factors that result in extended and complex humanitarian situations. Through 2021, political turmoil has exacerbated the impacts of drought, leaving a huge proportion of the country grappling with food insecurity. *The New Humanitarian* recently wrote an [insightful piece](https://www.thenewhumanitarian.org/news/2021/10/6/rural-drought-to-urban-shortages-Afghanistans-new-hungry) on this. <br />
<br />

### Citations

- Raleigh, C., Linke, A., Hegre, H., Karlsen. J. (2010). “Introducing ACLED-Armed Conflict Location and Event Data.” Journal of Peace Research 47(5) 651- 660. Data downloaded on 30/10/2021 from [https://acleddata.com/](https://acleddata.com/)
- Global Administrative Areas (2020). “GADM database of Global Administrative Areas, version 3.6.” Data downloaded on 30/10/2021 from [https://gadm.org/data.html](https://gadm.org/data.html)
- Pebesma, E. (2018). “Simple Features for R: Standardized Support for Spatial Vector Data.” The R Journal, 10(1), 439–446. [doi: 10.32614/RJ-2018-009](https://doi.org/10.32614/RJ-2018-009)
- Dowle, M., et al. (2021) “ data.table: Extension of 'data.frame’ ” [https://r-datatable.com](https://r-datatable.com), [https://Rdatatable.gitlab.io/data.table](https://Rdatatable.gitlab.io/data.table), [https://github.com/Rdatatable/data.table](https://github.com/Rdatatable/data.table)
- Garnier, S., Ross, N., Rudis, R., Camargo, P.A., Sciaini, M., Scherer, C. (2021). “viridis - Colorblind-Friendly Color Maps for R.” doi: 10.5281/zenodo.4679424, R package version 0.6.2, [https://sjmgarnier.github.io/viridis/](https://sjmgarnier.github.io/viridis/)

<br /> <br /> <br /> <br />
[Back to main](https://cadooley.github.io/)
<br /> <br />
[![twitter](/maps/twitter_t_logo_small.png)](https://twitter.com/Claire_Dooley)
&nbsp;
[![github](/maps/GitHub-Mark-64px_small.png)](https://github.com/cadooley)
