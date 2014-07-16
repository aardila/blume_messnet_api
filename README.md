blume_api
=============

An API for the [BLUME data of Berlin](http://www.stadtentwicklung.berlin.de/umwelt/luftqualitaet/de/messnetz/).

Current (unstable) version of the api is deployed at:
[blumeapi.herokuapp.com](http://blumeapi.herokuapp.com/)

* List of sensor stations (`/api/v1/stations`)
* Sensor data by year (`/api/v1/sensordata/:year`)
    * `/api/v1/sensordata/:year/csv` gets the data as csv
* Most recent sensor data (`/api/v1/recent`)
    * `/api/v1/recent/csv` gets the data as csv