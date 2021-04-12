# How to display a summary for each level in TreeList
This example illustrates how to display a summary (e.g. count|sum) for each level in TreeList.

The calculation starts when the data was initially loaded. Recursion was used in order to traverse all nodes 
and get the necessary data to calculate the total value for each level. After calculation, the [push](https://js.devexpress.com/Documentation/ApiReference/Data_Layer/ArrayStore/Methods/#pushchanges) API was used in order to insert one row on each level that contains the total value.

Note that this solution does not support remote operations.
