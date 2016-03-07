# Serialize to Excel from Text

In **Action Form**, you have the ability to save your data to reports and download it as CSV file. 

However, there is also the option to export the inputted data to an XLS file.  Setting it up is pretty simple - on an existing or new button add as action Serialize > Serialize to Excel from Text. Inside the handler you have the following settings:

**Pattern**

You can provide a pattern for the excel file. (Optional)

**Field Separator** 

Field, you can choose your the field separator from your text. Accepts expressions. (Optional, default value is ",")

**Handle duplicates**

You can choose how to handle when you already have a file with the same name. (Optional, default value is "Rename")

**Text field**

Here you can define what text will be serialized.For example, the [FirstName] and [LastName] fields. Keep in mind that these fields must exist within the form and you need to add their ID, not field name.  

**Use excel formulas**

With this option checked all formulas found will be applied. When a cell has a value that starts with = it will write it as an excel formula.
Example: =Sum(A1,A2)
To escape the = add a ' in front of it.
Example: '=Sum(A1,A2) this will be considered a normal string.

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

Lastly, fill in your form and hit Submit. Check your destination folder and you'll see the newly-created XLS file there. Open it and it will look like this: 

{% youtube %} https://www.youtube.com/watch?v=vAAjBXPbdIw {% endyoutube %}