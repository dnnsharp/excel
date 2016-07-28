# Import Into Database (Entity)

Import values from an Entity list into a database table. If the ID column is defined as an identity column in your database, row values for that column will be ignored during the insert. The insert action has a 10min Bulk Copy Timeout.

**Connection String**

Leave empty to conect to the DNN database. Connect to a different database by providing the name of a connection string from web.config or a connection string.

**TableName**

Select the table to import data into.

**InsertAllValues**

Check this option if you want to try and insert all properties from the entity list into the database table.

**Use first row as column names**

Check this option if you want to use the first row of the file as the property names of the new entity. (Optional)

If this option is not checked the entity will assign the names: Field + Index.


Ex: Field0, Field1, etc ...

**On Error**

Define a list of actions to run on error. Otherwise, an error message is returned which will contain the underlying error if debug mode is on.
