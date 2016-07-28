# Load Entities (CSV)

The action offers the posibility to load data into an entity list from a CSV text. Similar to Load Entities (SQL), add a button with Action Entities > Load Entities (Csv). You have the possibility to include all fields at once by ticking one single button.

**CSV**

The CSV that will be converted into an entity list.

**Field Separator**

The separator used in the CSV file. The accepted field separators are:
- "," i.e. comma
- ";" i.e. semicolon
- tab

**Entity Name**

The name of the enitity you want to create.

**Use first row as column names**

Check this option if you want to use the first row of the file as the property names of the new entity. (Optional)

If this option is not checked the entity will assign the names: Field + Index.


Ex: Field0, Field1, etc ...

**On Error**

Define a list of actions to run on error. Otherwise, an error message is returned which will contain the underlying error if debug mode is on.
