# Load Entities (Excel File)

The action offers the posibility to load data into an entity list from an Excel file. Similar to Load Entities (SQL), add a button with Action Entities > Load Entities (Excel File). You have the possibility to choose from which XLS file to import data, and even to include all fields at once by ticking one single button.

**File Path**

Specify the path to the excel file. 
The file path can be any of the following: 
- RelativeUrl: Portals/0/myfile.xls
- AbsoluteUrl:  http://sitealias/Portals/0/myfile.csv 
- LinkClickUrl:  /LinkClick.aspx?fileticket=19ZSKtRQ1lQ%3d
- PhysicalPath: pathToDnnInstance\Portals\0\myfile.csv

**Entity Name**

The name of the enitity you want to create.

**Include All Fields**

Check this option to retrive all columns of the excel file. (Optional)

**Use first row as column names**

Check this option if you want to use the first row of the file as the property names of the new entity. (Optional) 
If this option is not checked the entity will assign the names: Field + Index.
Ex: Field0, Field1, etc ...

**Remove Fields Names**

Check this option if you do not want to serialize the names of the fields.

**Use excel formulas**

With this option checked all formulas found will be applied. When a cell has a value that starts with = it will write it as an excel formula.
Example: =Sum(A1,A2)
To escape the = add a ' in front of it.
Example: '=Sum(A1,A2) this will be considered a normal string.

**Criteria**

Add a criteria that fielters the data. (Optional)

**Pattern**

You can provide a pattern for the excel file. (Optional)

**Handle duplicates**

You can choose how to handle when you already have a file with the same name. (Optional, default value is "Rename")

**File password**

Will add a password to the whole file, this way other users will not be able to see the content of the file. (Optional)

**Worksheet password**

Will add a password to the excel worksheet, now users are able to see the content of the file but are not able to edit it. (Optional)

**Folder**

Select the destination where the file will be stored.

**Store Absolute URL**

Provide a token name where to Store Absolute URL. (Optional)

**Store Relative URL**

Provide a token name where to Store Relative URL. (Optional)

**Store Physical Path**

Provide a token name where to Store Physical Path. (Optional)

This extension is also available for DNN Api Endpoint and Sharp Scheduler.

{% youtube %} https://www.youtube.com/watch?v=vAAjBXPbdIw {% endyoutube %}
