
# HasLegend Property

 **Last modified:** July 28, 2015

 _**Applies to:** Excel 2013 | Office 2013 | VBA_

 **True** if the chart has a legend. Read/write **Boolean**.


## Example

This example turns on the legend for the chart and then sets the legend font color to blue.


```
With myChart 
 .HasLegend = True 
 .Legend.Font.ColorIndex = 5 
End With
```
