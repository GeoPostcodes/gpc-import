## Table definitions
GeoPostcodes table definitions and import scripts.

<br>
#### Regions table

<table class="table table-bordered table-striped">
<thead>
  <tr><th width="150">Field name</th><th width="120">Field type</th><th>Description</th></tr>
</thead>
<tbody>
  <tr><td><b>ISO</b></td><td><code>Char(2)</code></td><td>ISO 3166-1 Country code</td></tr>
  <tr><td><b>Country</b></td><td><code>Char(50)</code></td><td>Country name</td></tr>
  <tr><td><b>Language</b></td><td><code>Char(2)</code></td><td>Language code</td></tr>
  <tr><td><b>Level</b></td><td><code>Integer</code></td><td>Administrative level</td></tr>
  <tr><td><b>Type</b></td><td><code>Char(50)</code></td><td>Type of administrative unit</td></tr>
  <tr><td><b>Name</b></td><td><code>Char(80)</code></td><td>Administrative division name</td></tr>
  <tr><td><b>Region1</b></td><td><code>Char(80)</code></td><td>Administrative division level 1</td></tr>
  <tr><td><b>Region2</b></td><td><code>Char(80)</code></td><td>Administrative division level 2</td></tr>
  <tr><td><b>Region3</b></td><td><code>Char(80)</code></td><td>Administrative division level 3</td></tr>
  <tr><td><b>Region4</b></td><td><code>Char(80)</code></td><td>Administrative division level 4</td></tr>
  <tr><td><b>ISO2</b></td><td><code>Char(10)</code></td><td>ISO 3166-2 Region code</td></tr>
  <tr><td><b>FIPS</b></td><td><code>Char(10)</code></td><td>NGA Geopolitical code (formerly FIPS PUB 10-4)</td></tr>
  <tr><td><b>NUTS</b></td><td><code>Char(10)</code></td><td>European statistical division code</td></tr>
  <tr><td><b>HASC</b></td><td><code>Char(10)</code></td><td>Hierarchical administrative subdivision code</td></tr>
  <tr><td><b>STAT</b></td><td><code>Char(20)</code></td><td>National statistics/census code</td></tr>
</tbody>
</table>

<br>
#### Places table

<table class="table table-bordered table-striped">
<thead>
  <tr><th width="150">Field name</th><th width="120">Field type</th><th>Description</th></tr>
</thead>
<tbody>
  <tr><td><b>ISO</b></td><td><code>Char(2)</code></td><td>ISO 3166-1 Country code</td></tr>
  <tr><td><b>Country</b></td><td><code>Char(50)</code></td><td>Country name</td></tr>
  <tr><td><b><u>Language</u></b></td><td><code>Char(2)</code></td><td>Language code</td></tr>
  <tr><td><b><u>ID</u></b></td><td><code>Integer</code></td><td>Record identifier</td>
  </tr><tr><td><b>Region1</b></td><td><code>Char(80)</code></td><td>Administrative division level 1</td></tr>
  <tr><td><b>Region2</b></td><td><code>Char(80)</code></td><td>Administrative division level 2</td></tr>
  <tr><td><b>Region3</b></td><td><code>Char(80)</code></td><td>Administrative division level 3</td></tr>
  <tr><td><b>Region4</b></td><td><code>Char(80)</code></td><td>Administrative division level 4</td></tr>
  <tr><td><b>Locality</b></td><td><code>Char(80)</code></td><td>Locality name</td></tr>
  <tr><td><b>Postcode</b></td><td><code>Char(15)</code></td><td>ZIP / Postal code</td></tr>
  <tr><td><b>Suburb</b></td><td><code>Char(80)</code></td><td>Locality subdivision</td></tr>
  <tr><td><b>Latitude</b></td><td><code>Double</code></td><td>Place latitude (WGS84 coordinates)</td></tr>
  <tr><td><b>Longitude</b></td><td><code>Double</code></td><td>Place longitude (WGS84 coordinates)</td></tr>
  <tr><td><b>Elevation</b></td><td><code>Integer</code></td><td>Elevation in meters</td></tr>
  <tr><td><b>ISO2</b></td><td><code>Char(10)</code></td><td>ISO 3166-2 Region code</td></tr>
  <tr><td><b>FIPS</b></td><td><code>Char(10)</code></td><td>NGA Geopolitical code (formerly FIPS PUB 10-4)</td></tr>
  <tr><td><b>NUTS</b></td><td><code>Char(12)</code></td><td>European statistical division code</td></tr>
  <tr><td><b>HASC</b></td><td><code>Char(12)</code></td><td>Hierarchical administrative subdivision code</td></tr>
  <tr><td><b>STAT</b></td><td><code>Char(20)</code></td><td>National statistics/census code</td></tr>
  <tr><td><b>Timezone</b></td><td><code>Char(30)</code></td><td>Time zone name (Olson)</td></tr>
  <tr><td><b>UTC</b></td><td><code>Char(10)</code></td><td>Coordinated Universal Time</td></tr>
  <tr><td><b>DST</b></td><td><code>Char(10)</code></td><td>Daylight saving time</td></tr>
  <tr><td><b>Area</b></td><td><code>Char(10)</code></td><td>Telephone area code</td></tr>
  <tr><td><b>Type</b></td><td><code>Char(1)</code></td><td>Record type (D = Delivery place, B = Business/Admin, M = Military)</td></tr>
  <tr><td><b>Entity</b></td><td><code>Char(100)</code></td><td>Entity description (business or administrative records)</td></tr>
  <tr><td><b>Primary</b></td><td><code>Char(1)</code></td><td>P = Primary place when a same postcode can be used for multiple records</td></tr>
</tbody>
</table>
