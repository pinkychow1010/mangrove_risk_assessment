# Mangrove Risk Assessment

### 03 May 2024

This projects aim to visualize mangrove data from Global Mangrove Watch between 2016 and 2020, as well as to assess their potential risk from sea level rise.
The folder contains a Jupyter notebook where the whole workflow is documented, a text file consisting the Earth Engine script for data inspection and download, and several figures from data visualization.

**Task 1: Investigating Mangrove Distribution**

The analysis of mangrove coverage within the designated site reveals notable fluctuations over the period under examination. Between 2016 and 2018, there was a clear increase in mangrove coverage, expanding from approximately 55.8 km2 to 57.4 km2. However, this growth trend was subsequently reversed, with a decline observed between 2018 and 2020, ending up in a total coverage of 54.8 km2.

The areas of notable change predominantly locates in the northern part of the site, particularly along the edges of existing mangrove clusters and adjacent to the riverbed.

![](https://github.com/pinkychow1010/mangrove_risk_assessment/blob/main/mangrove_ts.JPG)

<br>

**Task 2: Flood Risk Assessment**

NASADEM is a suitable dataset for assessing potential flood risk of mangrove, owing to its high spatial resolution and creditable quality. Limitations lie in the data precision, as sea level risk modelling requires highly precise elelvation data. Other alternative includes DeltaDTM.

In summary, the mangrove at the study site are highly exposed to sea-level rise, with around half of the mangrove risk to be flooded in a scanerio with 1 meter sea level rise.

![](https://github.com/pinkychow1010/mangrove_risk_assessment/blob/main/risk_assessment.JPG)

### References
Bunting, P.; Rosenqvist, A.; Hilarides, L.; Lucas, R.M.; Thomas, T.; Tadono, T.; Worthington, T.A.; Spalding, M.; Murray, N.J.; Rebelo, L-M. Global Mangrove Extent Change 1996 – 2020: Global Mangrove Watch Version 3.0. Remote Sensing. 2022

NASA JPL (2020). NASADEM Merged DEM Global 1 arc second V001 [Data set]. NASA EOSDIS Land Processes DAAC. Accessed 2020-12-30 from doi:10.5067/MEaSUREs/NASADEM/NASADEM_HGT.001
