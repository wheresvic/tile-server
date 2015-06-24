# Node.js tile server

This is a basic implementation of a node.js based vector tile server with data being served out of a postgis db

# TODO

* unit tests
 * db module
 * api routes
* performance
 * data caching (in-memory, redis)
 * hardcode geometry extent to skip querying db for tiles outside scope
* feature
 * raster tile service (via mapnik?)
 * login system