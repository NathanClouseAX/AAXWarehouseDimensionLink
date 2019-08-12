#### Import Model
Import the model file using the ModelUtil.exe tool.
`ModelUtil.exe -import -metadatastorepath=[path of the metadata store where model should be imported]
-file=[full path of the file to import]`

#### Build the imported models
In Visual Studio select the Dynamics 365 -> Build Models… menu. In the Model Build dialog select the newly imported AAXWarehouseDimensionLink model package and press the Build button.

#### Synchronize the database
In Visual Studio click the Dynamics 365 -> Synchronize Database… menu item and press the Synchronize button in the shown dialog.
