<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128572204/16.2.3%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T279980)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
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


