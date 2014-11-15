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

License
-------

The MIT License (MIT)

Copyright (c) 2014 Chris Bupp

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
