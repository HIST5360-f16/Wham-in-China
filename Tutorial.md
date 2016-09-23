Open a new project; set the CRS by typing EPSG 3415 in the filter box and choosing “South China Sea Lambert”
Set up your modern georeferencing ‘canvas’
Add Vector and load CHN_adm0.shp [a modern shapefile] to serve as georeferencing canvas.
Add Vector: CHN_adm1.shp

For all – change the “properties” so they are not solid. Turn “labels” on for one of the city files [you may have to use both of them]
Download China 1863 Map
Download Ifranview at http://www.irfanview.com/
Use your Ifraview to convert the JPG file to TIFF
In QGIS click on the Raster tab then slect georeferncer

Use the georeferencer to add the TIFF version as a raster layer 
In the Geoferencer select the add point button (looks like a yellow star)
	Add a point on the Raster file. 
	A box will open up (Enter Map Coordinates) 
	Select "From Map Canvas"
	Repeat this process 5 more times

    
    Have at least 3 in the western part of the country
    Have more than 3 in the eastern part of the country

Specify transformation settings (Gold Cog)
Select Start Georeferincing (Green Play button)
Compare geo-referenced map to modern shapefile

Save File