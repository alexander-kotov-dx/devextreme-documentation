---
##### shortDescription
Gets the value of any field linked with the current cell.

##### param(field): PivotGridField
The field whose value to return.

##### param(isCalculatedValue): boolean
Specifies whether or not to return a <a href="/Documentation/16_1/ApiReference/Data_Layer/PivotGridDataSource/Configuration/fields/#calculateSummaryValue">post-processed</a> value. Pass <i>false</i> here to get the initial summary value.

##### return: any
The field value.

---
Use this method when you need extra information about the current cell. You can use the value of any field to which the cell belongs.