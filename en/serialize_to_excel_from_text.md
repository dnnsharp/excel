# Serialize to Excel from Text

In **Action Form**, you have the ability to save your data to reports and download it as CSV file. 

However, there is also the option to export the inputted data to an XLS file.  Setting it up is pretty simple - on an existing or new button add as action Serialize > Serialize to Excel from Text. Inside the handler you have the following settings:

In the Pattern field, you can provide a pattern for the excel file. (Optional)
![][105]

In the Field Separator field, you can choose your the field separator from your text. (Optional, default value is ",")
![][106]

In the me] and [LastName] fields. Keep in mind that these fields must exist within the form and you need to add their ID, not field name.  
![][92] 

Then, you must select the folder to which the file is uploaded. 
![][93] 

Lastly, fill in your form and hit Submit. Check your destination folder and you'll see the newly-created XLS file there. Open it and it will look like this: 
![][94] 

**Action Grid** too offers the possibility to serialize to CSV, and now with the Excel addon you can serialize from entity list - basically some or all the entries of a grid of your choice. Similar to Serialize from Text, add a grid button with Action Serialize > Serialize from Entity List. You have the possibility to choose which entities to export to XLS, and even to include all fields at once by ticking one single button. 
![][95] 

Here is one example of such an exported grid: 
![][96] 

This extension is also available for DNN Api Endpoint and Sharp Scheduler. 

{% youtube %} https://www.youtube.com/watch?v=vAAjBXPbdIw {% endyoutube %}


[91]: https://sites.google.com/a/dnnsharp.com/action-form-v2/_/rsrc/1426773527546/extensions/excel/both%20buttons.png
[92]: https://sites.google.com/a/dnnsharp.com/action-form-v2/_/rsrc/1426773670625/extensions/excel/serialize%20to%20excel.png
[93]: https://sites.google.com/a/dnnsharp.com/action-form-v2/_/rsrc/1426773712952/extensions/excel/excel%20folder.png
[94]: https://sites.google.com/a/dnnsharp.com/action-form-v2/_/rsrc/1426773772222/extensions/excel/text%20excel.png
[95]: https://sites.google.com/a/dnnsharp.com/action-form-v2/_/rsrc/1426773826540/extensions/excel/serialize%20entity.png
[96]: https://sites.google.com/a/dnnsharp.com/action-form-v2/_/rsrc/1426774091559/extensions/excel/grid.png
[97]: http://www.dnnsharp.com/dnn/modules/action-form-builder/whats-new
[98]: http://www.dnnsharp.com/Support#opturl=%2Faction-form
[99]: http://www.dnnsharp.com/support/request-a-video-tutorial
[100]: https://www.google.com/a/UniversalLogin?service=jotspot&continue=https://sites.google.com/a/dnnsharp.com/action-form-v2/extensions/excel
[101]: /a/dnnsharp.com/action-form-v2/system/app/pages/recentChanges
[102]: /a/dnnsharp.com/action-form-v2/system/app/pages/reportAbuse
[103]: javascript:;
[104]: http://sites.google.com
[105]: https://c254fe5a-a-f1e965b1-s-sites.googlegroups.com/a/dnnsharp.com/action-form-v2/FillePattern.bmp 
[106]: https://c254fe5a-a-f1e965b1-s-sites.googlegroups.com/a/dnnsharp.com/action-form-v2/Field%20Separator.bmp