Collapse All Expand All Members Options: Show All  Members Options: Filtered   
---  
DriveWorks SDK Documentation  |   
---|---  
ProjectItemListDef Class Members   
See Also Properties Methods Events [Send Feedback](mailto:apisupport@driveworks.co.uk?subject=Documentation Feedback: topic4511.md)  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) : ProjectItemListDef Class  
---  
  
Include Inherited Members    
Include Protected Members  


Glossary Item Box

The following tables list the members exposed by [ProjectItemListDef](topic4511.md).

# Public Properties

| Name| Description  
---|---|---  
![Public Property](dotnetimages/publicProperty.gif)| [Columns](topic4527.md)| Gets the columns for the item list definition.   
![Public Property](dotnetimages/publicProperty.gif)| [Name](topic4528.md)| Gets the name of the item list definition.   
![Public Property](dotnetimages/publicProperty.gif)| [TypeDefinitions](topic4529.md)| Gets the definition of each item type which can provide the basis of an item in the item list.   
Top

# Public Methods

| Name| Description  
---|---|---  
Public Method| [AddItem](topic4517.md)| Adds a new item to this item list.   
Public Method| [AddTypeDefinition](topic4518.md)| Creates a new [ProjectItemListTypeDef](topic4533.md) instance and adds it to this [ProjectItemListDef](topic4511.md).   
Public Method| CreateObjRef|  (Inherited from System.MarshalByRefObject)  
Public Method| [DeleteItem](topic4519.md)| Removes a item from the item list.   
Public Method| [EditItem](topic4520.md)| Edits an existing item in this item list.   
Public Method| [GetData](topic4521.md)| Gets information about the item that have been added to the current project or specification.   
Public Method| [GetItems](topic4522.md)| Gets an collection of all items in this item list.   
Public Method| GetLifetimeService|  (Inherited from System.MarshalByRefObject)  
Public Method| [MoveItemDown](topic4523.md)| Moves an item down in the list of items.   
Public Method| [MoveItemUp](topic4524.md)| Moves an item up in the list of items.   
Public Method| [RemoveTypeDefinition](topic4525.md)| Removes a type definition from the item list.   
Public Method| [TryGetTypeDefinition](topic4526.md)| Gets the type definition for a specific dialog.   
Top

# Protected Methods

| Name| Description  
---|---|---  
Protected Method| MemberwiseClone| Overloaded. (Inherited from System.MarshalByRefObject)  
Top

# Public Events

| Name| Description  
---|---|---  
![Public Event](dotnetimages/publicEvent.gif)| [ColumnsChanged](topic4530.md)| Raised when the columns of the item list change.   
![Public Event](dotnetimages/publicEvent.gif)| [ItemsChanged](topic4531.md)| Raised when any items have been added/deleted/edited/moved.   
![Public Event](dotnetimages/publicEvent.gif)| [Renamed](topic4532.md)| Raised when [Name](topic4528.md) has changed.   
Top

# See Also

#### Reference

[ProjectItemListDef Class](topic4511.md)   
[DriveWorks Namespace](topic2159.md)


