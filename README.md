# Energy Transition

Mothership Coder Mission 2: [Living Environment Challenges](https://www.space4good.com/coder-missions/)

## Problem Definition
There is lack of information of the performance and return of investment (ROI) of different renewable energy sources located in different areas. 

## Example research questions
- There are several energy alternatives for [greenhouses in PZH](https://www.zuid-holland.nl/onderwerpen/energie/glastuinbouw/) that suggest the production of CO2 neutral corps (using geothermal energy, or residual heat from industries) but also (giving off energy from biomass). Can you design a plan that combines different energy sources to power greenhouses along with the surrounding neighborhoods and industries?

- Aquathermie energy from water, is being [suggested](https://www.zuid-holland.nl/actueel/nieuws/mei-2019/huizen-verwarmen/) as a potential energy source of the future. This involves creating heat energy networks thus aiming at industrial symbiosis. What is a feasible plan to deliver to policymakers in this regard? Can it involve local energy communities?

#### Others
- What combinations of energy sources and locations have the highest efficiency and Return on Investment from but not limiting to:
     - Wind turbines in land + at sea
     - Solar Panels in cities + farmland
     - Geothermal
     - Long term energy storage with water
- What energy type (wind, solar, geo) is best paired to serve what industry?
- How can you achieve the best efficiency by combining different sources for different uses (cooking, heating, lighting)?

## Deliverables
The participating team is asked to conduct the necessary research and build a prototype of a system able to:
- Investigate the suggested research questions and any additional relevant ones
- Find patterns in the historical and real-time data
- Simulate different future scenarios (trade-off analysis) 
- Calculate the financial projections of the various simulated scenarios for the local government
- Deliver a report on the findings and opportunity maps based on the results

## Stakeholders
- Households
- Local and national government
- Utility providers
- Producers of renewable energy facilities

## Public Geodata South Holland

Public geodata of the province of South Holland can be found [here](http://geoservices.zuid-holland.nl/arcgis/rest/services). 
You can find information about economy, soil, land, boundaries, environment and water.

#### User guide

1. Click on the link.
2. You can see that there is a thematic classification of folders (Folders).
3. For example, click Rural_area
4. You will now see a list of Services (it is also above) with MapServer in parentheses.
5. For example, click Rural_area / Rural_area_WFS (MapServer)
6. You will now see a list of layers.
7. At the top, you will see the ArcGIS Online Map Viewer option behind "View In:"
8. Click here. A map viewer is opened in a new tab. On the left-hand side under Content you will see Rural area WFS. This is the service that contains the layers that you just saw the list for.
9. Click on the triangle for Rural Area WFS. And you see the same layers appear that you saw in step 6. The default setting is for the NBP 2018 MANAGEMENT AREA layer to be on. Turn this off. This is a heavy file, which means that image building takes a long time.
10. Switch on the "Bicycle traffic intensity" layer. Points now appear in the map image.
11. Now click on the text "Intensity of bicycle traffic". Icons will now appear below this text.
12. Click on the second icon of a table. A table with data per point now appears below the map image.
13. You have now opened a map viewer via the link from the email. Turned on a data layer and opened the table.
14. For people who want to work with data, technical data is also useful, for example to see if a data layer consists of points, lines or surfaces, which area the layer covers or which columns of the table are in it. For this it is useful to click on the "All Layers and Tables" link from the previous tab.
15. The technical data are listed per layer of the service.
 
This guide is for a WFS because with it the data itself (Features, the F in WFS) is shared in accordance with an open standard. In a GIS application, for example, someone who is in Argentina can use this to do an analysis and make a map.

## Available data

- [Geothermie](https://atlas.zuid-holland.nl/GeoWeb54/index.html?viewer=Bodematlas)
- [Geothermal heat pits PZH (raw)](http://www.nationaalgeoregister.nl/geonetwork/srv/dut/catalog.search#/metadata/258F1008-8AF3-401E-982A-13D8BB551094) [(WFS)](https://geoservices.zuid-holland.nl/arcgis/services/Bodem/Bodem_energie_WFS/MapServer/WFSServer?&request=GetCapabilities&service=WFS)
- [Zonnewijzer](http://pzh.maps.arcgis.com/apps/MapSeries/index.html?appid=e2c8d3d5971046afacbde6dbe3d2bc36)
- [Warmtetransitieatlas](http://pzh.maps.arcgis.com/apps/MapJournal/index.html?appid=4c8e61a776eb4a6e8aaec99653d22b62)
- [Heat networks PZH](http://www.nationaalgeoregister.nl/geonetwork/srv/dut/catalog.search#/metadata/A78B8300-C293-4DFB-85E6-2B58DF27508D) [(WFS)](https://geoservices.zuid-holland.nl/arcgis/services/Bodem/Bodem_signaleringskaarten_WFS/MapServer/WFSServer)
- [Heat transport pipeline PZH(raw)](http://www.nationaalgeoregister.nl/geonetwork/srv/dut/catalog.search#/metadata/2F34AB70-6A5C-4C80-8718-EEB2D7984B27) [(WFS)](https://geoservices.zuid-holland.nl/arcgis/services/Bodem/Bodem_signaleringskaarten_WFS/MapServer/WFSServer)
- [Wind](https://www.arcgis.com/apps/webappviewer/index.html?id=d2ca33dc195b40b29c7855132998ca56&extent=50331.4683%2C437486.5411%2C98185.1641%2C467357.0008%2C28992)
- [Energie en bodem in de Signaleringskaarten voor PZH](http://www.signaleringskaarten.nl/) [(data)](http://nationaalgeoregister.nl/geonetwork/srv/dut/catalog.search#/search?isChild='false'&resultType=details&fast=index&_content_type=json&from=1&to=20&sortBy=relevance&any_OR__title=signaleringskaarten&geometry=region:http:%2F%2Fgeodatastore.pdok.nl%2Fregistry%2Flocation%23Zuid-Holland_province)
- [Greenhouses](https://www.pdok.nl/introductie/-/article/basisregistratie-topografie-brt-topnl)
*Search for Functioneel gebied (point) with attribute kassengebied.

-  Energy The Hague
     - [link](https://ckan.dataplatform.nl/dataset/energielabels-postcode-5-niveau-den-haag-2016/resource/17baa0b9-e819-4f0d-b0fe-f219aa4ee559)
     - [link](https://ckan.dataplatform.nl/dataset/warmtekoudeopslagsystemen/resource/512860c7-cced-4189-affd-4dfb312db3d6)
     - [link](https://ckan.dataplatform.nl/dataset/warmtekoudevoetafdruk/resource/02b284e7-aba2-4993-a923-86676871fd57)
     - [link](https://ckan.dataplatform.nl/dataset/blokverwarming/resource/778451b4-bfbc-46d3-a5b9-08299a2f4376)
     - [link](https://ckan.dataplatform.nl/dataset/tevervangenleidingendenhaag1/resource/1b392e4c-c72f-4409-818e-b79525c1516f)
     - [link](https://ckan.dataplatform.nl/dataset/warmtenet-dh-2015112/resource/9a2963c1-b08e-45db-86a4-4ea78b85c930)
     - [link](https://ckan.dataplatform.nl/dataset/warmteobjecten-dh3/resource/e1fcff0d-1974-46ef-9ef3-8da8d30a992f)
     - [link](https://ckan.dataplatform.nl/dataset/riothermie-potentielepanden-den-haag-2016/resource/88cf3d2e-67d0-41d6-abee-2b6155749ef0)
     - [link](https://ckan.dataplatform.nl/dataset/warmtenet-kansgebieden-denhaag-2016/resource/ca5086ea-5a91-469e-9139-f3be1b9afb72)
     - [link](https://ckan.dataplatform.nl/dataset/stadsverwarming-dh/resource/ebeb6db8-28bd-4b6c-935f-49ba3e64701c)
     - [link](https://ckan.dataplatform.nl/dataset/wko-negatief-advies/resource/4c056ea7-4a07-492f-8708-26eeb60fda35)
 
- Geothermal Energy potential The Hague
     - [link](https://ckan.dataplatform.nl/dataset/geothermie-positief-advies-den-haag/resource/b1f08565-b031-41d4-9467-b78c9ee55d61)
     - [link](https://ckan.dataplatform.nl/dataset/geschiktheid-geothermie-den-haag-2013/resource/b001f1b1-d36a-4f1a-924c-4c418ed0c008)
 
- Electricity
     - [link](https://ckan.dataplatform.nl/dataset/lichtmasten1/resource/f015483b-025b-4a4b-8ab4-3ace5c10d150)
     - [link](https://ckan.dataplatform.nl/dataset/lichtmasten/resource/3ce26c9f-c632-4347-950b-ff6081d09c38)
     - [link](https://ckan.dataplatform.nl/dataset/armaturen/resource/1887141e-5e5b-42ea-a087-9db85d605628)
     - [link](https://ckan.dataplatform.nl/dataset/kabels/resource/5820cd51-ca24-4942-aaa2-20d75d9152ae)

