## How To Set The Best View For Information Layer
In case you have a set of elements displayed by the InformationLayer, you might want to be able to display all of them in the visible area of the map and to set the optimal zoom for them. This can be done by using the Best View feature of the RadMap. To use it you have to call the GetBestView() method of the InformationLayer and pass its items to it. This method will return a LocationRect object which represents the best view for the items in the InformationLayer. You can use it in order to adjust the RadMap center and zoom level.

To see and run the example, please use the 'Open in VS' button and execute the project inside Visual Studio.

[//]: <keywords:DataMapping, Location, ZoomLevel, ZoomRange, HotSpot, ToolTip>
