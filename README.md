US Judicial Boundaries
======================

*Boundaries for:*
 - US Court of Appeals (11 + DC)
 - US District Courts

Where's the Data Coming From?
-----------------------------

 1. Started with [Court Jurisdiction Boundaries](http://gis.stackexchange.com/questions/3533/gis-layer-of-usa-state-court-jurisdiction-boundaries)
     - Which originally came from this broken link: http://www.fedstats.gov/mapstats/fjd
 2. Dissolved into District Courts (based on `JDNAME` attribute from the original data)
 3. Used [Wikipedia](http://upload.wikimedia.org/wikipedia/commons/d/df/US_Court_of_Appeals_and_District_Court_map.svg) to Merge into Appeals court
 4. Manually added:
     - US Virgin Islands
     - Guam
     - Northern Mariana Islands
 5. Converted to geojson
