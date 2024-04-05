# Tamil Nadu Election Results- 2021

### Overview
I have built a Power BI Report on Tamil Nadu Assembly Election 2021 Results. The Sixteenth Tamil Nadu Legislative Assembly Election was held on 6 April 2021, to elect representatives from the 234 constituencies in the Indian State of Tamil Nadu. The Dravida Munnetra Kazhagam (DMK) won the election, ending the decade-long reign of the All India Anna Dravida Munnetra Kazhagam (AIADMK). 

### Steps followed

* The Election results data was taken from the Indiavotes.com website, as the data was not found in the official election commission website.

* The data set was a loaded into the Power Query editor of Power BI. Data cleaning was done in the power query editor for a proper data.

* The Most important thing in the project is the "CONSTITUENCY MAP". It was obtained by collecting the different types of maps with different extensions.

* .shp is shape file map, .prj is Border file map, .dbf is constituency map. But PowerBI accepts the shape map in TopoJson extension. So all these files were merged to form a TopoJson extension map file.

* Then the data was loaded into the front end of the PowerBI, there the relationship between tables were done.

* The party flag/ symbol was obtained as a web URL and it was used in the slicers to visualize the data.

* The charts were imported and showcase the seats won and votes% of the party and bookmark was added.

* The constituency wise winner with the Party was visualized in the table format.

* Thus the Election Results of Tamil Nadu 2021 was visualized in the Power BI using the constituency Map.

  
### Dashboard
![Capture](https://github.com/Balaji-Amaranathan/TamilNadu-Election-Results-2021/assets/165944320/d3688371-7aeb-4c70-901a-227243768c62)
