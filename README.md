# Fusioncharts-VB.net-wrapper
This is a wapper program for FusionCharts in VB.net


## Usage Guide
### Installing
Installation of this package is as simple as copying the "FusionCharts.vb" file to "App_Code" directory of your project.

After installing the package you can use it as follows in any of your web page
```
 'First you have to Import the namespace in the page
 Imports FusionCharts.Charts 
 
 'Dim <object name> As New Chart("<chart type>", "<chart name>", "<width of the chart>", "<height of the chart>", "<data type>", <data as string>)    
 Dim newChart As New Chart("msline", "myChart", "600", "350", "json", jsonData.ToString())
 
```
### Example
