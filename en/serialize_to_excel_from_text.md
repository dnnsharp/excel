# Serialize to Excel from Text

In **Action Form**, you have the ability to save your data to reports and download it as CSV file. 

However, there is also the option to export the inputted data to an XLS file.  Setting it up is pretty simple - on an existing or new button add as action Serialize > Serialize to Excel from Text. Inside the handler you have the following settings:

**Pattern**

You can provide a pattern for the excel file. (Optional)

**Field Separator** 

Field, you can choose your the field separator from your text.
Accepts expressions. (Optional, default value is ",")

**Handle duplicates**

You can choose how to handle when you already have a file with the same name. (Optional, default value is "Rename")

In the **Text field**, you can define what text will be serialized.For example, the [FirstName] and [LastName] fields. Keep in mind that these fields must exist within the form and you need to add their ID, not field name.  

You also have the option to **Use excel formulas**. With this option checked all formulas found will be applied.

With the password fields you can add passwords to your excel file. The **File password** field will add a password to the whole file, this way other users will not be able to see the content of the file. While with the **Worksheet Password** field you will add a password to the excel worksheet, now users are able to see the content of the file but are not able to edit it.

Then, you must select the **Folder** to which the file is uploaded. 

Lastly, fill in your form and hit Submit. Check your destination folder and you'll see the newly-created XLS file there. Open it and it will look like this: 

{% youtube %} https://www.youtube.com/watch?v=vAAjBXPbdIw {% endyoutube %}