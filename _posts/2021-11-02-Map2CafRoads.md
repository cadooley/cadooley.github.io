
![map2](/maps/map2_caf_roads.jpg)

# Map 2: Central African Republic roads | 2nd Nov 2021

<br />

**#30DayMapChallenge themes:** lines & OpenStreetMap <br />
<br />

### Data

- HOTOSM Central African Republic Roads (Humanitarian OpenSTreetMap Team, 2020; [https://data.humdata.org/dataset/hotosm_caf_roads](https://data.humdata.org/dataset/hotosm_caf_roads)) <br />
<br />

### Code

Map code available on [GitHub](https://github.com/cadooley/map_challenge_2021/blob/main/RScripts/map2_caf_roads.R). <br />
<br />
I used the *sf* package (Pebesma, 2018) to convert data into an easy-to-use format. <br />
<br />

### About the map


With a long history of armed conflict and ongoing civil war that begin in 2012, Central African Republic grapples with economic and development challenges. The [World Bank estimated](https://www.worldbank.org/en/country/centralafricanrepublic/overview#1) that 71% of Central African Republic’s population was living below the international poverty line in 2020 and the [UN’s latest round of Human Development Index](http://hdr.undp.org/en/countries/profiles/CAF) scoring saw the country ranked 188 out of the 189 countries assessed. In March 2021, UNOCHA launched [The Humanitarian Response Plan](https://reports.unocha.org/en/country/car/card/3Odeib7bvk/) outlining a strategy for assisting an estimated 1.84 million extremely vulnerable people, many of whom live in very hard-to-reach areas. <br />
<br />
Successfully delivering resources and services, such as food packages and health care, to a large number of people requires very detailed planning and efficient logistics management, and spatial data can play a significant role in reaching this goal. In particular, road network data is often vital for planning routes and ensuring timely delivery of humanitarian programmes. <br />
<br />
The map above shows road data across Central African Republic collected by the [Humanitarian OpenStreetMap Team](https://www.hotosm.org/where-we-work/central-african-republic/) (HOTOSM). HOTOSM work in crisis-affected regions across the globe and collect data through open mapping campaigns and projects that see thousands of volunteers contributing data. Because of the crowdsourcing nature of this data collection approach, HOTOSM are able to cover a wide area quickly, however, this also means that the data is inevitably patchy in areas that are inaccessible and/or have limited high-quality satellite imagery. In spite of their limitations, the roads data collected and provide by HOTOSM is often the best available and is therefore exceptionally valuable for humanitarian response. <br />
<br />
With transparency about data limitations, programme teams are able to weigh up the pros and cons of different datasets, and often use many datasets in combination to assess where people live and how to reach them. Additionally, data can be even more valuable when it includes attributes such as year and/or season of collection as well as specific characteristics. For example, the Central African Republic roads data displayed in the image also includes surface type for each road section, equipping programme teams with knowledge of whether a road will be ‘dirt’, ‘asphalt’, ‘gravel’, etc, further supporting planning decisions. <br />
<br />
Attempts to improve the availability of road network data also comes from the research and technology sectors, where computer algorithms and machine learning approaches have been developed to automate the extraction of roads from satellite imagery. While there are still challenges with different terrain types, extraction of very small roads and costs associated with accessing high quality satellite imagery, automated processes provide huge potential for future road data availability. For a review of these approaches, see [Wang et al (2016)](https://www.sciencedirect.com/science/article/pii/S2095756416301076#!) and for a recent study showing progress in this field see [Brewer et al (2021)](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0253370). <br />
<br />


<br />

### Citations

- Humanitarian OpenSTreetMap Team. (2020). “HOTOSM Central African Republic Roads”. Downloaded from [https://data.humdata.org/dataset/hotosm_caf_roads]( https://data.humdata.org/dataset/hotosm_caf_roads) on 01/11/2021
- Pebesma, E. (2018). “Simple Features for R: Standardized Support for Spatial Vector Data.” The R Journal, 10(1), 439–446. [doi: 10.32614/RJ-2018-009](https://doi.org/10.32614/RJ-2018-009)
- Wang, W., Yang, N., Zhang, Y., Wang, F., Cao, T., Eklund, P. (2016). “A review of road extraction from remote sensing images”. Journal of Traffic and Transportation Engineering (English Edition). [https://doi.org/10.1016/j.jtte.2016.05.005](https://doi.org/10.1016/j.jtte.2016.05.005)
- Brewer, E., Lin, J., Kemper, P., Hennin, J., Runfola, D. (2021). “Predicting road quality using high resolution satellite imagery: A transfer learning approach”. PLoS ONE 16(7): e0253370. [https://doi.org/10.1371/journal.pone.0253370](https://doi.org/10.1371/journal.pone.0253370)

<br /> <br /> <br /> <br />
[Back to main](https://cadooley.github.io/)
<br /> <br />
[![twitter](/maps/twitter_t_logo_small.png)](https://twitter.com/Claire_Dooley)
&nbsp;
[![github](/maps/GitHub-Mark-64px_small.png)](https://github.com/cadooley)
