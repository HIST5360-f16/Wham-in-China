# Georeferencing with WHAM!

![Wham! in China](/Wham! in China.jpg)

1 Open a new project; set the CRS by typing EPSG 3415 in the filter box and choosing “South China Sea Lambert”
![China CRS](http://i1092.photobucket.com/albums/i405/finbar01/China%20CRS_zpszf7rnulx.png)
2 Set up your modern georeferencing ‘canvas’
* Add Vector and load CHN_adm0.shp [a modern shapefile] to serve as georeferencing canvas.
* Add Vector: CHN_adm1.shp

![Wham! in China 2](/Wham! in China 2.jpg)

3 For all – change the “properties” so they are not solid. Turn “labels” on for one of the city files [you may have to use both of them]
![China Vector layer](http://i1092.photobucket.com/albums/i405/finbar01/China%20Vector%20Layer_zps6ozagnm2.png)
4 Download China 1863 Map

5 Download Ifranview at http://www.irfanview.com/
* Use Ifraview to convert the JPG file to TIFF
![Geo Screenshot 2](/Geo Screenshot 2.png)
 
6 In QGIS click on the Raster tab then select georeferncer
* Use the georeferencer to add the TIFF version as a raster layer 
![Geo Screenshot](/Geo Screenshot.png)

7 In the Geoferencer select the add point button (looks like a yellow star)
* Add a point on the Raster file. 
* A box will open up (Enter Map Coordinates) 
* Select "From Map Canvas"
* Repeat this process 5 more times (Have at least 3 in the western part of the country
 Have more than 3 in the eastern part of the country)

8 Specify transformation settings (Gold Cog)

9 Select Start Georeferincing (Green Play button)
![Georefrenced map](http://i1092.photobucket.com/albums/i405/finbar01/China%20Georefrenced_zpsc56t5hgi.png)
10 Compare geo-referenced map to modern shapefile

11 Save File

![Wham! in China 3](/Wham! in China 3.jpg)
