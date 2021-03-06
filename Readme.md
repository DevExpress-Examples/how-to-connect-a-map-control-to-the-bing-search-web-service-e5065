<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/ConnectBingSearchProvider/Form1.cs) (VB: [Form1.vb](./VB/ConnectBingSearchProvider/Form1.vb))
<!-- default file list end -->
# How to connect a map control to the Bing Search web service


<p>This example demonstrates how to provide the capability to search for a specific place on a map using the Search panel. </p><p>To enable search in the map control, do the following</p><p>- Create an <a href="http://documentation.devexpress.com/#WindowsForms/clsDevExpressXtraMapInformationLayertopic"><u>InformationLayer</u></a> and add it to the map. </p><p>- Create an instance of the <a href="http://documentation.devexpress.com/#WindowsForms/clsDevExpressXtraMapBingSearchDataProvidertopic"><u>BingSearchDataProvider</u></a> and assign it to the <a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraMapInformationLayer_DataProvidertopic"><u>InformationLayer.DataProvider</u></a> property. </p><p>- Specify the Bing Maps key via the <a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraMapBingMapDataProvider_BingKeytopic"><u>BingMapDataProvider.BingKey</u></a> property. </p><p><br />
The Search panel appears automatically (since the <a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraMapBingSearchDataProvider_ShowSearchPaneltopic"><u>BingSearchDataProvider.ShowSearchPanel</u></a> property is set to <strong>true</strong> by default) after you connect to the<strong> Bing Search web</strong> service. </p><p><br />
Note that if you run this sample as is, you will get a warning message informing that the specified Bing Maps key is invalid. To learn about how to register a Bing Maps account and create a key for it, refer to the <a href="http://documentation.devexpress.com/#WindowsForms/CustomDocument15102"><u>How to: Get a Bing Maps Key</u></a> tutorial.</p><br />


<br/>


