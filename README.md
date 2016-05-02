# exchange-search
This repository will contain project management, tickets, etc.

The code developed will happen in a branch of the MapLoom project and a branch of the HyperMap project.

 * https://github.com/terranodo/maploom

 * https://github.com/terranodo/HHypermap

The main branches are called exchange-search in both.

Minimum Viable Product:

 - List based search implementation using MapLoom as the backend and HyperMap with ElasticSearch as the backend, allows quick map based preview and adding the layer to the map.

Ongoing work:
 - CSW-T interface to accept catalog pushes and to be able to perform pushes to GeoNode instances as remote layers.
 - Parallelize harvesting for elastic search core in order to be able to fill the database in hours instead of days.
 - ESRI Rest support directly in OL3
 - ESRI Rest support on MapProxy

Mockup: 
![search mockup](https://cloud.githubusercontent.com/assets/5114135/14870816/90a466aa-0ca2-11e6-94d6-31e7ee2591e9.png "Search Mockup")
