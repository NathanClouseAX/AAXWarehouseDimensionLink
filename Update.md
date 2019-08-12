#### Upgrade Model
Execute the ModelUtil.exe command to replace/upgrade the model:

`ModelUtil.exe -replace -metadatastorepath=[path of the metadata store]
-file=[full path of the file to import]`

#### Build the imported models
In Visual Studio select the Dynamics 365 -> Build Models… menu. In the Model Build dialog select the newly imported AAXWarehouseDimensionLink model package and press the Build button.

#### Synchronize the database
In Visual Studio click the Dynamics 365 -> Synchronize Database… menu item and press the Synchronize button in the shown dialog.
