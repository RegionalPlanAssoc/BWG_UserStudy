# Brooklyn Greenway User Study Data Sources and Methodology
Datasets related to the Brooklyn Waterfront Greenway User Study

## Numina Sensors
Numina sensors use machine learning to detect what type of object, whether a pedestrian, bicycle, truck, or car, is moving across their view, without storing any personal identifying information. The pathways of each pedestrian or vehicle are tracked across the view, allowing for more detailed data on how people are using the greenway, not just how many. Personal identifying information is not collected. For this study, all 32 Numina sensors were installed on light poles along the 29 mile greenway, collecting data for 14 months, between March 1, 2023 and April 30, 2024. Sensor locations were chosen to provide as much coverage of the greenway as possible, as well as incomplete sections of the greenway and off-greenway sites of interest, such as near transit or bridges. However, due to restrictions on which light poles were eligible to host sensors, there are several gaps in coverage, especially along the southern half of the greenway.

Obtaining approval and permits from the New York City government for installing the sensors on street poles took over two years, far longer than anticipated. Negotiating with the electrical utility ConEdison over how to measure and bill the power also took several months. In addition, installation costs for the electrician proved much higher than was initially budgeted. While there were delays and added costs, they did not derail the project. Unfortunately, it did mean that data collection from the intercept and online surveys was not simultaneous with the Numina sensor data.

The project faced several technical challenges, as expected with any cutting-edge technology like the Numina sensors. Due to the delays in getting approvals for sensor installation, survey collection was completed before the sensors were installed, instead of being simultaneous as intended. Sensor downtime, resulting from issues ranging from loss of power supply to software bugs to, in one case, a light pole being struck by a car, led to some gaps in the data. Loss of power to the sensors was the single biggest issue, as restoring power meant coordinating with DOT, Con Edison, and the electrician contractor to diagnose the problem and solve it, which proved to be too costly and time consuming. As a result, three of the 32 sensors were not functional during the data collection period, and an additional three were operational for only half the data collection period. Software issues were able to be resolved remotely, though some sensors still lost thousands of hours of data. Overall, however, 18 of the 32 sensors were able to collect data for at least 90% of the study period. Where possible, efforts were made to account for gaps in the data. Otherwise, for time periods when data was unavailable or unreliable for an individual sensor, values have been removed from the dataset. Environmental factors such as camera obstructions and low lighting at night may also have some effect on data quality, but those issues are harder to detect, and therefore account for, in the data. 

The Numina count dataset released alongside the Brooklyn Greenway Study contains both pedestrian and cyclist counts for each operational sensor, by hour, for the data collection period of March 1, 2023 through April 30, 2024. Specifically, for each sensor’s field of view, a screenline was drawn to specifically capture Greenway users, excluding pedestrians and cyclists crossing perpendicular to the Greenway, for example.


### Numina sensor locations
- A-01 McGuinness Blvd and Eagle St
- A-02 Franklin St and Freeman St
- A-03 West St and Greenpoint Ave
- A-04 Quay St and Franklin St
- A-05 Kent Ave and N 9th St
- A-06 Kent Ave and S 4th St
- A-07 Kent Ave and Broadway
- B-01 Naval Cemetery Landscape
- B-02 Flushing Ave and Vanderbilt Ave
- B-07 Flushing Ave and Cumberland Ave*
- B-03 Sands St and Navy St
- B-04 Navy St and York St
- B-05 Jay St and York St
- B-06 Jay St and Prospect St
- C-01 Furman St and Old Fulton St
- C-02 Atlantic Ave and Columbia St
- D-01 Hamilton Ave and Van Brunt
- D-02 Imlay St and Verona St
- D-03 Conover St and Pioneer St*
- D-04 Henry St and Bay St
- E-01 3rd Ave and 29th St*
- E-02 2nd Ave and 59th St
- E-03 67th St and Colonial Rd
- F-01 Shore Rd and Bay Ridge Ave
- F-03 Shore Parkway Greenway and Bay Parkway
- F-04 Bay 52nd and W 52nd*
- G-01 Surf Ave and 15th St*
- G-02 Neptune Ave and Ocean Pkwy*
- H-01 Jamaica Bay Greenway and Flatbush Ave (West)
- H-02 Jamaica Bay Greenway and Flatbush Ave (East)
- H-03 Jamaica Bay Greenway and Canarsie Circle
- H-04 Pennsylvania Ave and Jamaica Bay Greenway*

*Little or no data collected

## Intercept Surveys
Between June 2021 and September 2022, the project’s field research team collected over 1,000 intercept surveys at seven locations along the greenway. After removing incomplete surveys, 909 responses remain. Surveys were collected at different times of day, weekdays and weekends, and different times of year. Greenway users were stopped and asked to answer a five minute survey, including questions regarding trip purpose, origin and destination, whether their trip had a connection to transit, and demographic information. A complete list of questions can be found [here](https://github.com/RegionalPlanAssoc/BWG_UserStudy/blob/main/Brooklyn%20Greenway%20User%20Study%20-%20Intercept%20Survey%20Variables.pdf). The survey results were weighted based on nearby sensor counts based on whether the respondent was a pedestrian or cyclist, which segment of the greenway they were using, and the time of year.
 

### Survey Results Weighting
Intercept surveys were collected for six of the eight segments of the greenway. Field researchers surveyed Greenway users systematically to capture responses at different times of day, and different times of year.

### Field Research Team
Jack Darcey, Wisely Chang Wu, Jacob Boersma, Daniel Flores, Daniel Kim, Max Murgio, Matthew Shore, Joaquim Stevenson-Rodriguez, Greg Suter, Maribel Tale, Eric Thompson, Jess Wachtler, Jade White

## Online Research Panel
In addition to the intercept surveys collected on the greenway itself, the project team used the online surveying service Qualtrics to survey 330 residents of the neighborhoods surrounding the greenway. Respondents were selected to accurately reflect the demographics of the neighborhoods surveyed. The online survey allowed for more detailed questions about general greenway use, as well as the opportunity to hear from greenway non-users.

## Additional Data Sources
US Census Bureau. American Community Survey. 2018-2022.
NYC Department of City Planning. [ZoLa: Zoning & Land Use Application](https://zola.planning.nyc.gov/l/zoning-district/PARK?layer-groups=%5B%22street-centerlines%22%2C%22zoning-districts%22%5D&search=false#14/40.71591/-73.94995).
Regional Plan Association, Office of the Brooklyn Borough President, New York Academy of Medicine, and Hester Street. [The Comprehensive Plan for Brooklyn](https://www.brooklynbp.nyc.gov/wp-content/uploads/2023/10/Comprehensive-Plan-1.pdf), 2023.
NYC Department of Transportation. [Citywide Mobility Survey](https://www.nyc.gov/html/dot/html/about/citywide-mobility-survey.shtml). 2022.
National Oceanic and Atmospheric Administration. Local Climatological Data (LCD) Dataset. 2023-2024.
