<!-- default file list -->
*Files to look at*:

* [MainPage.xaml](./CS/UsingGraphColorizer/MainPage.xaml) (VB: [MainPage.xaml](./VB/UsingGraphColorizer/MainPage.xaml))
<!-- default file list end -->
# How to colorize map contours loaded from Shapefiles using the Graph colorizer


<p>This example demonstrates how to paint map contours loaded from a Shapefile (<strong>Countries.shp</strong>) using the graph colorizer. </p><br />



<h3>Description</h3>

<p>To accomplish this task, create a graph colorizer (the <a href="http://help.devexpress.com/#Silverlight/clsDevExpressXpfMapGraphColorizertopic"><u>GraphColorizer</u></a> object) and assign it to the <a href="http://help.devexpress.com/#Silverlight/DevExpressXpfMapMapControl_Colorizertopic"><u>MapControl.Colorizer</u></a> property. <br />
</p><p>And finally, specify the desired set of colors in the <a href="http://help.devexpress.com/#Silverlight/clsDevExpressXpfMapColorCollectiontopic"><u>ColorCollection</u></a> object that is accessed via the <a href="http://help.devexpress.com/#Silverlight/DevExpressXpfMapMapColorizer_Colorstopic"><u>MapColorizer.Colors</u></a> property. </p><br />


<br/>


