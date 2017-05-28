# shp-mongo-import.py
Import Shapefile geospatial vector format into MongoDB

Fast shapefile import into MongoDB using Python

Before running ensure you have the PyMongo module installed:

`pip install pymongo`

Example usage:

`python shp-mongo-import.py -f shapes.shp -d geospatial -c shapes`

Additional parameters are required if your server is not on your local machine or if your database requires authentication. Use the "--help" flag or see the example below.

`python shp-mongo-import.py -f shapes.shp -s host.example.com -d mydb -c shapes -u user -p password` 

Script requires MongoDB 3.2 or higher (prior releases do not support bulk operations), and was developed using Python 2.7 and a MongoDB 3.4 server.
