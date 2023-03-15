# Chicago Crime Analysis

Author: Milene Carmes Vallejo

<img width="585" alt="image" src="https://user-images.githubusercontent.com/112773242/225435506-01417cd3-a1fc-4207-a90e-f0e1812824e9.png">

image from: https://www.flickr.com/photos/195041916@N08/51903154236/


## Data:

 Chicago Data Portal: https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2
 
 This dataset reflects reported incidents of crime (with the exception of murders where data exists for each victim) that occurred in the City of Chicago from 2001 to 01/2023. 
 

## Business problem:

Answer a series of questions about trends in crimes in Chicago for a reporter for the local newspaper. 
 
 
 
## Methods: 

- Processed and analyzed a dataset of crimes in Chicago from 2001 to 2023 including the type of crime, exact date/time, lat/long, District/ward, was there an arrest.

* Worked with time series in Python - preparing the Datetime Index, separate the full dataset by years and months

+ Exploratory data analysis utilizing Pandas, Matplotlib,  Seaborn.

- Created a dashboard and a story in Tableau.

## Results

### Crimes Across the Years:

####  Is the total number of crimes increasing or decreasing across the years? 

![image](https://user-images.githubusercontent.com/112773242/225438135-aaa8df17-6cb8-4422-af9e-b0b7fdf6b055.png)

The number of crimes decrease over the years.


#### Are there any individual crimes that are doing the opposite ?

 ![image](https://user-images.githubusercontent.com/112773242/225442207-40793ac7-ba6e-4c9e-8cd3-e81628d0292c.png)

 
There are some crimes that increase in some years like:

- DECEPTIVE PRACTICE (2015-2018)

- MOTOR VEHICLE THEFT - 2022

- INTERFERENCE WITH PUBLIC OFFICER - (2010-2014)

- HOMICIDE - 2016, 2020, 2021

- CONCEALED CARRY LICENSE VIOLATION (2016-2019)

- CRIMINAL SEXUAL ASSAULT (2016-2022)

- OBSCENITY (2013-2018)

- OTHER NARCOTIC VIOLATION and PUBLIC INDECENCY had different peaks along the years

- STALKING (2021-2022)

- WEAPONS VIOLATION (2016-2022)


### Comparing Months:
#### What months have the most crime? What months have the least?

![image](https://user-images.githubusercontent.com/112773242/225446351-62dccd1d-d1a3-4050-9ae9-886b8a05ccfd.png)

July is the month that has the highest number of crimes and February is the month with the lowest number of crimes.

### Are there any individual crimes that do not follow this pattern? If so, which crimes?

![image](https://user-images.githubusercontent.com/112773242/225446860-486af42c-8872-4b59-a014-bf329f05cee5.png)

In the plots above we can see that there are many crimes when the peak was not in July, like:

- PUBLIC INDECENCY - the peak is in August

- OBSCENITY - the peak is in October,

- ASSAULT and KIDNAPPING and PUBLIC PEACE VIOLATION - the peak was in May,

- BURGLARY the peak was in August

- OFFENSE INVOLVING CHILDREN, PROSTITUTION and CRIMINAL TREPASS,DECEPTIVE PRACTICE - the peak is in January

- CONCEALED CARRY LICENSE VIOLATION the peak was in September

- CRIMINAL SEXUAL ASSAULT the peak was October,

- NARCOTICS - the peak was in March



## Create a Tableau story with the visualizations
https://public.tableau.com/views/Chicago_crime_project4/Story1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link


 ### Create a treemap to show the % distribution of each Crime Type
 
<img width="628" alt="image" src="https://user-images.githubusercontent.com/112773242/225449305-abcd912d-28de-4187-9aef-84c84263fb6d.png">
 
The most common type of crime is THEFT (21%)

### Comparing Police Districts

<img width="600" alt="image" src="https://user-images.githubusercontent.com/112773242/225450033-a7dc2107-d83f-4753-9488-c4b897827e0a.png">

### Comparing Total Crime by Day of the Week
<img width="587" alt="image" src="https://user-images.githubusercontent.com/112773242/225450584-ede1c999-4bee-4e9f-9e2e-257dc5310761.png">


### Forecasting Crimes

<img width="578" alt="image" src="https://user-images.githubusercontent.com/112773242/225451336-74a58be5-4533-42e4-a728-350ec1a7a1cb.png">

### Map - Crime Locations
<img width="644" alt="image" src="https://user-images.githubusercontent.com/112773242/225451536-a0ca3432-8c40-446b-886b-0547bd1479d3.png">



##  Create a Tableau Dashboard
https://public.tableau.com/app/profile/milene.carmes.vallejo7059/viz/Chicago_crime_Dashboard_core/MainDashboard_update?publish=yes

<img width="573" alt="image" src="https://user-images.githubusercontent.com/112773242/219900546-511e3d1a-6fd0-4e72-b807-2062ac3bdf25.png">


