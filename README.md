# pbi-globalization
> A PowerBI visualization to show data through Latitudes and Longitudes :earth_americas:

## How it works

Give the visualization a latitude + longitude coordinate, data value, and location name. The globe will display a databar at each Lat/Long location with the length determined by the value. Tooltips will hover over the **top 10** values (or top x if there is less than 10 rows).

![Image of Visualization](https://github.com/buttsj/pbi-globalization/blob/master/assets/globe_img1.PNG)

## Installing this Visualization

Navigate to the /dist/ folder and import the .pbiviz file into your PBI Desktop/Web App report.

![Image of Icon](https://github.com/buttsj/pbi-globalization/blob/master/assets/globe_icon.PNG)

## Contributors

Jack Butts [Portfolio](https://www.dreameater.net)

## Release History

* v1.0
	* Builds globe and data bars at given lat/long location
    * Slowly rotates around the globe's axis
    * Data can be filtered by outside visualizations
* v1.1
    * Globe no longer auto-rotates
    * Globe can be rotated with mouse click and drag
    * Data is now scaled down by the median of the data set (easier to see all data bars on globe) 
* v1.2
    * Data is now scaled down by the amount of the value, for better visibility
    * New required data bucket for a name of the Lat/Long location
    * Tooltips now appear on the Top 10 values (displaying Name + Value)
* Possible future features:
    * Allow click filtering on data bars
    * Let user choose how many tooltips to show on screen