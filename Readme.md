<!-- default file list -->
*Files to look at*:

* [MainPage.xaml](./CS/LoadShapeFile/MainPage.xaml)
* [MainPage.xaml.cs](./CS/LoadShapeFile/MainPage.xaml.cs)
<!-- default file list end -->
# How to: Load vector data from Shapefile


This example demonstrates how to load vector data from Shapefile.


<h3>Description</h3>

To load vector data from Shapefile, do the following.<br />1. Create a&nbsp;<strong>VectorFileLayer </strong>object and add it&nbsp;to the&nbsp;<strong>MapControl.Layers</strong> collection.<br />2. Create an instance of the&nbsp;<strong>ShapefileReader </strong>class and assign&nbsp;the instance&nbsp;to the&nbsp;<strong>VectorFileLayer.FileReader</strong> property.<br />3. Create&nbsp;a&nbsp;<strong>MapFileSourceBase </strong>class descendant object, configure it&nbsp;and assign to the&nbsp;<strong>FileSource </strong>property of the instance.

<br/>


