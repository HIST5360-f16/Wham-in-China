# Georeferencing with
![Image 1](https://dl.dropboxusercontent.com/u/101767455/GIT%20HUB%202/Image%201.jpg)

Purpose: The following tutorial provides instructions for georeferencing China.  By the end of the tutorial, users will be able to compare a modern basemap with a historical map of China.  Users will be able to see and identify once existing chinese territories.  Dotting the tutorial below are pictures of the 1980s band WHAM!  The inclusion of WHAM!, or any popular culture element, adds a layer of familiarity for the user - in this exercise, students.  The student may not know or have heard of WHAM!, but identifying some point of interest a student may have with a geo-referencing activity such as this activity helps to: engage the student, draw connections the student may not have been aware of going into the project, and adds a layer of interest in the project that the student may not have had at the onset.  In this exercise and when conducting additional independent research, students will come to learn that WHAM! visited China in 1985.  As an instructor, you may want to have a student pick another popular culture event or person and see if the student is able to draw connections when geo-referencing a historical map of China (or any other country).  

![Wham! in China 3](/Wham! in China 3.jpg)

1 To begin, open QGIS from your computer's Start Menu.

![QGIS](https://dl.dropboxusercontent.com/u/101767455/GIT%20HUB%202/QGIS%201.PNG)

2 Once QGIS is open, select Project in the upper left hand corner of the screen.

![PROJECT](https://dl.dropboxusercontent.com/u/101767455/GIT%20HUB%202/QGIS%202.PNG)

3 Within the Project menu, select New.  You may also press Ctrl+N

4 Then press Ctrl+shift+P, and toggle on the setting “Enable on the fly CRS transformation”. Set the CRS by typing EPSG 3415 in the filter box and choosing “South China Sea Lambert”
![China CRS](http://i1092.photobucket.com/albums/i405/finbar01/China%20CRS_zpszf7rnulx.png)

5 Set up your modern georeferencing ‘canvas’: this will give us a base map on which to work.
* Add a vector layer by selecting CHN_adm0.shp [a modern shapefile] to serve as geo-referencing canvas.
![Add Layer](http://i70.photobucket.com/albums/i94/QueenOfTheMoon/Add%20Layer%20Screenshot.png)

* Also, add Vector: CHN_adm1.shp

6 For both layers – change the “Properties” so they are not solid by right clicking on the layer, and choosing properties. 
[Property Layer](http://i70.photobucket.com/albums/i94/QueenOfTheMoon/Properties%20Screen.png)
*Then select the Style option on the left hand side of the screen. Select the option Simple fill, and change the fill style option to no brush. 
[Property Layer 2](http://i70.photobucket.com/albums/i94/QueenOfTheMoon/Properties%20II.png)
Turn “labels” on for one of the city files [you may have to use both of them] by selecting properties again, and selecting the labels option. 
[Label](http://i70.photobucket.com/albums/i94/QueenOfTheMoon/Label%20Option.png)
![China Vector layer](http://i1092.photobucket.com/albums/i405/finbar01/China%20Vector%20Layer_zps6ozagnm2.png)
7 Download the China 1863 Map 

![wham china 12](https://dl.dropboxusercontent.com/u/101767455/GIT%20HUB%202/wham%20china%201.jpg)

8 Download Ifranview at http://www.irfanview.com/
* Use Ifraview to convert the JPG file to TIFF
![Geo Screenshot 2](/Geo Screenshot 2.png)
 
9 In QGIS click on the Raster tab at the top of your screen then select geo-referencer. This will allow us to layer the 1863 map onto the shapefile of modern-day China.
* Use the geo-referencer to add the TIFF version as a raster layer 
![Geo Screenshot](/Geo Screenshot.png)

10 In the Geoferencer select the add point button (looks like a yellow star)
* Add a point on the Raster file. 
* A box will open up (Enter Map Coordinates) 
* Select "From Map Canvas"
* Repeat this process 5 more times (Have at least 3 in the western part of the country
 Have more than 3 in the eastern part of the country. It is also important to georeference different types of points. Remember, coastlines and waterways (like rivers) change over time, but the locations of cities usually stays the same, so be sure to georeference at least 2 cities: one in the east and one in the west).

11 Specify transformation settings (Gold Cog)

12 Select Start Georeferincing (Green Play button)
![Georefrenced map](http://i1092.photobucket.com/albums/i405/finbar01/China%20Georefrenced_zpsc56t5hgi.png)
13 Compare geo-referenced map to modern shapefile

14 Play around with the settings on your various layers: change border widths and labels to see how they compare. See what information you can glean from doing this.

15 Save File.  To Save, navigate to the Project menu.  You may also press Ctrl+S to save, but it is preferred for first time saving to prefrom a Save As.  To Save As, use the same navigation as a Save or you may press Ctrl+Shift+S.
![SAVE](https://dl.dropboxusercontent.com/u/101767455/GIT%20HUB%202/save.png)

16 Once saved, you may exit QGIS.  To exit, navigate to the Project menu and click on Exit QGIS.  Or, you may press Ctrl+Q.

![SAVE](https://dl.dropboxusercontent.com/u/101767455/GIT%20HUB%202/Exit.PNG)

![Wham! in China](/Wham! in China.jpg)
