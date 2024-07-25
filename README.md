# Mapping asylum

### Aim
- How are asylum seekers distributed throughout The Netherlands?

### Data collection
- For my basemap, I used data from the Centraal Bureau voor Statistiek: https://www.cbs.nl/nl-nl/dossier/nederland-regionaal/geografische-data/wijk-en-buurtkaart-2023. This also contained information on number of inhabitants and population density.
- For the data on the number of asylum seekers per municipality, I used the website from the Centraal Orgaan Asielopvang (COA): https://www.coa.nl/nl/locatiezoeker
- Information on the income per municipality also came from CBS: https://opendata.cbs.nl/#/CBS/nl/dataset/85343NED/table?ts=1678533033006

### Overview data analysis
- I used table joins, graduated layers and centroids in QGis to figure out the differences between municipalities
- Then I used AI2HTML for annotations and scrollama to turn it into a scrollytelling piece
 
### If I had more time:
- Add a dimension of the vote last election: do areas with more asylum seekers vote pro-immigration parties, or not?
- Add a tooltip to hover over municipalities or build a tool so readers can look up their municipality
- Change the representation of the circles to triangles that differ in height, so that it's easier to see the difference between them
