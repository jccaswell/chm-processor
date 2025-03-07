Collapse All Expand All Members Options: Show All  Members Options: Filtered   
---  
DriveWorks SDK Documentation  |   
---|---  
FilePickingOptions Class Members   
See Also Properties Methods [Send Feedback](mailto:apisupport@driveworks.co.uk?subject=Documentation Feedback: topic9902.md)  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.GroupMaintenance Namespace](topic9628.md) : FilePickingOptions Class  
---  
  
Include Inherited Members    
Include Protected Members  


Glossary Item Box

The following tables list the members exposed by [FilePickingOptions](topic9902.md).

# Public Constructors

| Name| Description  
---|---|---  
![Public Constructor](dotnetimages/publicConstructor.gif)| [FilePickingOptions Constructor](topic9908.md)| Creates a new instance of [FilePickingOptions](topic9902.md).   
Top

# Public Properties

| Name| Description  
---|---|---  
![Public Property](dotnetimages/publicProperty.gif)| [ExcludeFiles](topic9912.md)| Collection of files that should not be included.   
![Public Property](dotnetimages/publicProperty.gif)| [ExcludeFolders](topic9913.md)| Collection of directories that should not be included.   
![Public Property](dotnetimages/publicProperty.gif)| [IncludeFiles](topic9914.md)| Designed to negate exclude folders, not include files outside the root.   
![Public Property](dotnetimages/publicProperty.gif)| [IncludeFolders](topic9915.md)| Designed to negate excluded folders, not add folders outside the root.   
![Public Property](dotnetimages/publicProperty.gif)| [RootFolder](topic9916.md)| The top most directory to select files from.   
Top

# Public Methods

| Name| Description  
---|---|---  
Public Method| [GetFiles](topic9909.md)| Gets an effective collection of all files that are included based on the current options.   
Public Method| [GetModel](topic9910.md)| Creates a new representation of all files and folders within the root and their inclusion state.   
Public Method| [UpdateModel](topic9911.md)| Takes an existing model and updates it to match the current file system.   
Top

# See Also

#### Reference

[FilePickingOptions Class](topic9902.md)   
[DriveWorks.GroupMaintenance Namespace](topic9628.md)


