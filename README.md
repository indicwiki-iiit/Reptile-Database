# Reptile-Database
I have uploaded four files as below

1) Reptiles_iNat_ID.xlsx: 
   This contain the data I have scraped initially it has 11245 rows with 14 attributes. It has very dense data.
   Some of the data within a field present in Czech language along with English. 
   I have assigned a unique Id for all the data I have scrapped so that I can combine the data from multiple sources
   I have search the every reptile species in https://www.inaturalist.org/ (it has very rich information and link to multiple databases for any species).
   Wherever I am able to locate the reptile in iNaturalist site, I saved its URL in "Reptiles_iNat_ID.xlsx"

2) iNat.xlsx:
    This data I have scraped from https://www.inaturalist.org/ based on URL I fetched in "Reptiles_iNat_ID.xlsx". This file has 7461 rows with 1047 attributes. 
    Data is very spar and similar information is spread across with different attribute name. It require manual effort to merge these 1047 attributes.
    This file has link to English Wikipedia page also out of 7461 rows 6221 rows to have Wikipedia link. 
    I am planning to fetch the infobox from existing Wikipedia page
    
3) db_all.xlsx:
    https://www.inaturalist.org/ contain the links to other databases, I have scrapped this links to enhance my data in future.
    I have got links 36 different databases and on an average every reptile has links to 9 other databases.
    
4)  iNat_Attr.xlsx:
    This sheet contain the 1047 attributes present in iNat.xlsx file, and I manually working on these attribute to merge them.
