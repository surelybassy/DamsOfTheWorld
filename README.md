# DamsOfTheWorld
Cleaning, Analysis and Visualisation of Data about Dams

![All Dams](DamImages/AllDams.png?raw=true "All Dams")

# The Data

The data set came from the World Bank Data Catalog and contains information about 6155 dams around the world.
https://datacatalog.worldbank.org/dataset/global-dams-database

Additional information gathered from the Internation Commision of Large Dams.
https://www.icold-cigb.org

## Cleaning

Of the 59 features in the data set, several contained mostly null values or information that would provide little analytical insight, so these were dropped.

Looking at the data in the purpose column, I could see several spelling errors and variations, so cleaned these up to make things more standardised. 

# Analysis

### Purposes

From the information in the data set, we can see that at least 45% of the dams are used for irrigation purposes, 34% provide some sort of hydroelectricity and 5% are used to provide water.
![Purposes](DamImages/Purposes.png?raw=true "Purposes")

### Exploring the Annual Power Production

There wasn't a hude amount of information on the power production for all the dams, but for the information I had I created a boxplot to see the spread of the power produced in different countries.

![Annual Power Production](DamImages/PowerProductionBoxplot.png?raw=true "Annual Power Production")

### Exploring the Number of Dams by Country

![Countries Top 10](DamImages/NumberPerCountry.png?raw=true "Dams by Country Top 20")

China has by far the most dams, with more than double the USA. With a large amount of geographical information for India I thought it would be interesting to take a closer look at the dams there.

## A Closer Look
### India
![India](DamImages/IndiaAll.png?raw=true "India")

### The River Olt, Romania 

Romania generates just under 30% of it's power from Hyrdoelectricity. The river Olt has 24 dams providing power, below these are mapped to see how they are spread along the river.

![River Olt](DamImages/RiverOrt.png?raw=true "River Olt")


