# PyCon 2019 datasets
Datasets for PyCon 2019 Education Summit Mini-Sprint: Workbooks that teach Python through scientific data exploration

All datasets in this directory are publically available and sourced from primary research articles or government databases. A description of each data collection can be found below:

### Coral Bleaching:
These datasets summarize coral reef station data from the [NOAA Coral Reef Watch](https://coralreefwatch.noaa.gov/vs/). The NOAA Coral Reef Watch program uses satellite data to provide current reef environmental conditions to quickly identify areas at risk for coral bleaching. Bleaching is the process by which corals lose the symbiotic algae that give them their distinctive colors. If a coral is severely bleached, disease and death become likely.

There are six included datasets for six of the NOAA coral reef stations in Fiji, the Florida Keys, the Galapagos, the Great Barrier Reef, Hawaii, and Palau. The columns are defined as follows:
* Date of data collection
* Latitude of station
* Longitude of station
* Sea Surface Temperature (in Celsius)
* Hot Spots (magnitude of instantaneous heat stress, potentially resulting in coral bleaching. The scale ranges from 0 to 5 °C. HotSpot values of 1 °C or more indicate heat stress leading to coral bleaching)
* Degree Heating Weeks (accumulated bleaching heat stress over a 12 week period. The scale ranges from 0 to 20 °C-weeks. Significant coral bleaching usually occurs when the DHW value reaches 4 °C-weeks. At 8 °C-weeks, widespread bleaching is likely and significant mortality can be expected.)
* Bleaching Alert Area (measure of coral bleaching thermal stress as follows: 0-no stress, 1-bleaching watch, 2-bleaching warning, 3-bleaching alert lvl 1, 4-bleaching alert lvl 2)

### Plant Archaeology:
These datasets compile, from published sources, the sample records of archaeobotanical (plant) remains from archaeological sites located in southwest Asia, central Anatolia and Cyprus dated to the Pre-Pottery Neolithic or earlier. These datasets were downloaded from the UK Archaeology Data Service, the [Origins of agriculture: archaeobotanical database](https://archaeologydataservice.ac.uk/archives/view/origins_nerc_2018/index.cfm).

The data was collected by Michael Wallace, Alexandra Livarda, Michael Charles, and Glynis Jones, from the Universities of Sheffield, Nottingham, and Oxford. The research article explaining their findings is entitled "Re-analysis of archaeobotanical remains from pre- and early agricultural sites provides no evidence for a narrowing of the wild plant food spectrum during the origins of agriculture in southwest Asia" and can be read in its entirety [here](https://link.springer.com/article/10.1007%2Fs00334-018-0702-y).

The four included datasets are as follows
* plant_metadata.csv: Definitions for all column headers
* plant_site_names.csv: Location information for each archaeological site in the study
* plant_samples.csv: Details of individual samples
* plant_taxa.csv: Summary data for each plant taxa recorded

### Chilean Earthquakes
In April 24, 2017 a magnitude 6.9 earthquake occured just west of Valparaiso, Chile, as the result of thrust faulting on or near the subduction zone interface between the Nazca and Pacific tectonic plates. This same section of the plate boundary ruptured in a magnitude 8.0 earthquake in March 1985. These two datasets list all magnitude 2.5+ earthquakes in central Chile in 1985 and 2017. They were obtained from the United States [Geological Survey (USGS) Earthquake Catalog](https://earthquake.usgs.gov/earthquakes/search/). A rectangular region around Valparaiso, Chile was selected using the custom geographic region option. 

The datasets include the time, latitude, longitude, depth, and magnitude for each earthquake that occured. More information about each column in the datasets can be found [here](https://earthquake.usgs.gov/data/comcat/data-eventterms.php).

