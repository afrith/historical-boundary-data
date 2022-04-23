This repo is a collection of geospatial data relating to past political/administrative boundaries in South Africa which I have obtained or digitized from various sources.

## TBVC boundaries

The `tbvc` directory contains GeoJSON files describing the boundaries of the former Republics of Transkei, Bophuthatswana, Venda, and Ciskei. These four states received nominal independence from South Africa between 1976 and 1981, under the apartheid government's policy of "separate development". Their independence was not recognized by any other countries. All four were reintegrated into South Africa on 27 April 1994.

Each file contains a series of multipolygons, one representing the extent of the territory at the date of nominal independence, and the rest representing areas ceded by South Africa to the state after independence. In the case of Bophuthatswana there is also one polygon representing an area retroceded back to South Africa.

The sources I used to construct this data are:
* Historic maps of the 1:50,000 and 1:250,000 series published by the Trigonometrical Survey Office (now the Chief Directorate: National Geo-spatial Information), which can be download from the [CDNGI Geospatial Portal](http://www.cdngiportal.co.za/cdngiportal/).
* The agreement between the governments of South Africa and Venda concerning international boundaries, published under Government Notice No. R.2014 of 1979.
* The agreement between the governments of South Africa and Ciskei concerning international boundaries, published under Government Notice No. R.961 of 1982.
* The Bophuthatswana Border Extension Act, No. 8 of 1978.
* The Borders of Particular States Extension Act, No. 2 of 1980, its amendment acts, and the proclamations made under the act (details of which are given in the "descrip" field in each GeoJSON file).
* Cadastral boundary data from the Office of the Chief-Surveyor General; the easiest source for this is [from PlanetGIS](https://planetgis.co.za/browse.php?id=11).
* Cadastral survey diagrams, which can be downloaded from the [CSG website](http://csg.drdlr.gov.za/esio/searchindex.htm).

## provinces-1910.geojson

Boundaries of the four former provinces of South Africa as they were at the creation of the Union in 1910 (and as they remained until the Transkei was made nominally independent in 1976).

I constructed this several years ago, so I don't recall the exact sources I used. The boundary of the OFS is the same as current provincial boundaries, as is the northern border of Natal (except the eastern end around Simandlengentsha and Pongola). The Cape–Natal boundary still corresponds to current municipal boundaries. I think I digitized the Cape–Transvaal boundary from old Trig Survey maps.

## provinces-1994.geojson

Boundaries of the provinces of South Africa as they were under the Interim Constitution in 1994 (and remained until 2006).

This is from an offical shapefile though I am not sure where exactly I received it from. I made one correction; the official shapefile showed the farms Drumleary 130 and Stanford 127 (near Matatiele) as a small exclave of KZN surrounded by the Eastern Cape, but it is clear from the text of the Interim Constitution that these farms were indeed included in the Eastern Cape.
