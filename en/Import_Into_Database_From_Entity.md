# Import Into Database (Entity)

Import values from an Entity list into a database table. If the ID column is defined as an identity column in your database, row values for that column will be ignored during the insert. The insert action has a 10min Bulk Copy Timeout.

**Connection String**

Leave empty to conect to the DNN database. Connect to a different database by providing the name of a connection string from web.config or a connection string.

**TableName**

Select the table to import data into.

**InsertAllValues**

Check this option if you want to try and insert all properties from the entity list into the database table.

**Properties**

Select the specific columns of the excel file that you wish to retrieve. This field is ignored if Include All Fields is checked.

**Merge Existing Values**

Check this option if you want to try and update all values from the entity list that have a corresponding row in the database table. 

This option can increase the execution time for large amounts of data.

**Delete Non-Existing Values**

Check this option if you want to try and delete all values from the database table that do not have a corresponding item in the entity list.

This option can increase the execution time for large amounts of data.

**On Error**

Define a list of actions to run on error. Otherwise, an error message is returned which will contain the underlying error if debug mode is on.
