# DENVER_COFFEE_SHOP-_

💾 The data

I have assembled information from three different sources (locations
, neighborhoods, demographics

):
Starbucks locations in Denver, Colorado

    "StoreNumber" - Store Number as assigned by Starbucks
    "Name" - Name identifier for the store
    "PhoneNumber" - Phone number for the store
    "Street 1, 2, and 3" - Address for the store
    "PostalCode" - Zip code of the store
    "Longitude, Latitude" - Coordinates of the store

Neighborhoods' geographical information

    "NBHD_ID" - Neighborhood ID (matches the census information)
    "NBHD_NAME" - Name of the statistical neighborhood
    "Geometry" - Polygon that defines the neighborhood

Demographic information

    "NBHD_ID" - Neighborhood ID (matches the geographical information)
    "NBHD_NAME' - Nieghborhood name
    "POPULATION_2010' - Population in 2010
    "AGE_ " - Number of people in each age bracket (< 18, 18-34, 35-65, and > 65)
    "NUM_HOUSEHOLDS" - Number of households in the neighborhood
    "FAMILIES" - Number of families in the neighborhood
    "NUM_HHLD_100K+" - Number of households with income above 100 thousand USD per year

Starbucks locations were scrapped from the Starbucks store locator webpage by Chris Meller
.
Statistical Neighborhood information from the City of Denver Open Data Catalog, CC BY 3.0 license.
Census information from the United States Census Bureau. Publicly available information.
