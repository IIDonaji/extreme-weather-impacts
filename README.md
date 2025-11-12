# Identifying the impacts of extreme weather (Assignment 3 for EDS-223)

## About
Identifying the impacts of a series extreme winter storms by estimating the number of homes in Houston, Texas metropolitan area that lost power on February 2021 and analyze if there where any disproportion impacts. 

#### Learning outcomes
- Identify locations that experienced power outages using VIIRS night lights data
- Estimate the number of homes affected by blackouts
- Examine whether blackout impacts were disproportionately experienced across different socioeconomic groups

Data:

**VIIRS Night Lights Data (VNP46A1)**
- NASA's Visible Infrared Imaging Radiometer Suite onboard the Suomi satellite
- Tiles h08v05 and h08v06 covering the Houston area
- Dates: 2021-02-07 (before storms) and 2021-02-16 (after storms)
- Source: NASA's Level-1 and Atmospheric Archive & Distribution System Distributed Active Archive Center (LAADS DAAC)
- Accessed via: [NASA Worldview](https://worldview.earthdata.nasa.gov/)

**OpenStreetMap - Roads**
- Highway and road network data for the Houston metropolitan area
- File: `gis_osm_roads_free_1.gpkg`
- Source: [Geofabrik Download Server](https://download.geofabrik.de/)

**OpenStreetMap - Buildings**
- Residential building footprints for the Houston metropolitan area
- File: `gis_osm_buildings_a_free_1.gpkg`
- Source: [Geofabrik Download Server](https://download.geofabrik.de/)

**U.S. Census Bureau - American Community Survey (ACS)**
- 5-Year estimates (2015-2019) Texas census tract level
- Geodatabase: `ACS_2019_5YR_TRACT_48_TEXAS.gdb`
- Includes median household income and demographic data
- Source: [U.S. Census Bureau](https://www.census.gov/programs-surveys/acs)

#### Author

[Ixel M.](https://github.com/IIDonaji)

### Information on the Course
This analysis was completed for EDS 223: Geospatial Analysis and Remote Sensing at the Bren School of Environmental Science & Management, UC Santa Barbara.

- Instructor: Annie Adams
- Assignment: Homework 3 - Identifying the Impacts of Extreme Weather
- Date: October 2025
### References
- Wikipedia. 2021. "2021 Texas power crisis." Last modified October 2, 2021. https://en.wikipedia.org/wiki/2021_Texas_power_crisis
- Assignment instructions: EDS 223 Course Website