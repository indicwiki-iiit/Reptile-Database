# Reptile-Database

Major source of my data is https://www.inaturalist.org/. I have scrapped the data for 7461 reptiles and after cleaning the data I have 43 attributes (mentioned below).  
Some of the attributes are very sparse; I am planning to merge these attributes with other relevant sections in Jinja template.
Except 'Reference', 'Further Reference' and 'Wikipedia' I have translated the remaining attributes in Hindi.

Wikipedia attribute is a link given to reptiles in English Wikipedia. Out of 7461, 6222 reptiles do have English wikipedia links. I am planning to fetch the infobox and image from English Wikipedia.
I have also captured the link for reptiles in other datasource (36 different data sources). On an average for any reptile I have links to seven other data sources.
The Link format I used in db_all.xlsx is "<database key id>: <database url for reptile>". I have given a local Unique ID  for every reptile so that I can use it to fetch the data from different datasource.

Attributes:
Common Names_Hindi	
Description_Hindi
Basic Info_Hindi
Summary_Hindi
Physical  Appearance_Hindi
Physiology_Hindi
Venom_Hindi	
Biology_Hindi
Habitat_Hindi
Diet_Hindi
Habits_Hindi
Behavior and Ecology_Hindi
Distribution_Hindi
Conservation_Hindi
Endangerment_Hindi
History_Hindi
Evolution_Hindi
Races_Hindi
Subspecies_Hindi
Taxonomy and Etymology_Hindi
Taxonomy_Hindi
Taxonomy Hierarchy_Hindi
Other Info_Hindi
Etymology_Hindi	
Life-Span_Hindi
Anatomy_Hindi
Autotomy_Hindi
Ecology_Hindi
Reproduction and Dimorphism_Hindi
Uses_Hindi
Captivity_Hindi	
Human Interaction_Hindi
As Pets_Hindi
Medicinal Properties_Hindi
Economic Importance_Hindi
Parasites_Hindi	
Defense_Hindi
Predator and Threats_Hindi
Thermoregulation_Hindi	
Seasonal Adaptation_Hindi					
References	
Further Reference	
Wikipedia
