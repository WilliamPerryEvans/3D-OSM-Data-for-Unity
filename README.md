# Importing 3D GIS Data into Unity
{%hackmd -gP7sZzbSw2Rv-OUA6YxJA %}
## OpenStreetMap :arrow_right: Blender :arrow_right: Unity 


### Steps to creating a 3D terrain in Unity from OpenStreetMap

#### The instructions below should guide you through taking OSM data within Blender and exporting it into Unity to create a 3D terrain for a game.

- [ ] Download the zip file in [BlenderGIS](https://github.com/domlysz/BlenderGIS)
    - Click the green button `Code` and then click `Download ZIP`
- [ ] Install the add-on by going to `Edit` and then clicking on `Preferences` and then selecting `Add-ons` in the lefthand panel. Select `Install` and then locate the ZIP file on your computer, then press `Install Add-on`
    - There is an option if you expand the add-on under Basemaps called `Cache folder` - make sure you have this pointing towards a folder on your computer where you can store GIS data temporarily.
- [ ] After installing, you should have a button on the main screen of Blender to the right of Object called GIS. Go to `Web geodata` then `Basemap`. Select the source you want (whether Google, OSM or another data source). 
- [ ] You will then be shown a map of the world. Scroll to the location you want, or press `g` and type in a location. Once you have your area in view, press `e` as a shortcut to snip the screen in view.
- [ ] To get the OSM data, go back to `GIS` and select `Web geodata` followed by `Get OSM`. You will then be able to select all the various datasets of interest to you. Be sure to select `Elevation from object`. Press ok and give your computer a little time to import the data—it can take some time depending on how much there is, so keep your area of interst reasonable; i.e. don't try to import an entire city unless you happen to have a super computer 🖥
- [ ] Finally, export as an .obj file to a folder on your computer, and import into Unity. You now have an entire geographic area from the real world in your game!

