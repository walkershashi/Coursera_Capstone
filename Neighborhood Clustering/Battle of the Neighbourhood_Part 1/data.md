The data used analysis and recommendation contains the neighbourhood details for the New York City and Toronto City.

### Data Provider

For the clustering of the <code>New York</code> neighbourhood and segmenting them, the data is available <a href = 'https://geo.nyu.edu/catalog/nyu_2451_34572'>here</a>

Neighborhood has a total of 5 boroughs and 306 neighborhoods. In order to segement the neighborhoods and explore them, we will essentially need a dataset that contains the 5 boroughs and the neighborhoods that exist in each borough as well as the the latitude and logitude coordinates of each neighborhood. 


For the <code>Toronto</code> Data Set, the data is provided through:
<ul>
    <li>Postal Code and Neighborhood: Wikipedia</li>
    <li>Co-Ordinates of the Neighbourhood: <a href = 'https://cocl.us/Geospatial_data'>GeoSpatial Data set</a></li>
    <li>Localities of Each Neighbourhood: FourSquare Api
</ul>

### Data Acquisition

The data is available in the form of the table on the wiki page <a href = 'https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M'>here</a>
The data is scraped from the given web page and is tranformed from the table into a dataframe which is readily available for segmentation.

The table tag has a class associated with it, <code>class = wikitable sortable</code>


