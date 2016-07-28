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

**Properties**

Select the specific columns of the excel file that you wish to retrieve. This field is ignored if Include All Fields is checked.

**On Error**

Define a list of actions to run on error. Otherwise, an error message is returned which will contain the underlying error if debug mode is on.
