Collapse All Expand All Members Options: Show All  Members Options: Filtered   
---  
DriveWorks SDK Documentation  |   
---|---  
PackageGroupProcess Class Members   
See Also Properties Methods Events [Send Feedback](mailto:apisupport@driveworks.co.uk?subject=Documentation Feedback: topic9925.md)  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.GroupMaintenance Namespace](topic9628.md) : PackageGroupProcess Class  
---  
  
Include Inherited Members    
Include Protected Members  


Glossary Item Box

The following tables list the members exposed by [PackageGroupProcess](topic9925.md).

# Public Properties

| Name| Description  
---|---|---  
![Public Property](dotnetimages/publicProperty.gif)| [IsStopped](topic9793.md)| Whether or no the process has been stopped. (Inherited from [DriveWorks.GroupMaintenance.CopyGroupProcess](topic9776.md))  
![Public Property](dotnetimages/publicProperty.gif)| [SourceGroup](topic9794.md)| The source group to copy from. (Inherited from [DriveWorks.GroupMaintenance.CopyGroupProcess](topic9776.md))  
![Public Property](dotnetimages/publicProperty.gif)| [TargetDirectory](topic9795.md)| Gets/sets the file location that the process output file/s will be saved to. (Inherited from [DriveWorks.GroupMaintenance.CopyGroupProcess](topic9776.md))  
Top

# Protected Properties

| Name| Description  
---|---|---  
![Protected Property](dotnetimages/protectedProperty.gif)| [Actions](topic9792.md)| The current actions to be executed. (Inherited from [DriveWorks.GroupMaintenance.CopyGroupProcess](topic9776.md))  
Top

# Public Methods

| Name| Description  
---|---|---  
Public Method| [CheckStopped](topic9782.md)| Checks to see if the process is canceled. (Inherited from [DriveWorks.GroupMaintenance.CopyGroupProcess](topic9776.md))  
Public Method![static \(Shared in Visual Basic\)](dotnetimages/static.gif)| [CreatePackageGroupProcess](topic9931.md)| Creates a new instance of the [PackageGroupProcess](topic9925.md) class.   
Public Method| [Dispose](topic9932.md)| Overloaded. Overridden.   
Public Method| [GetActions](topic9787.md)| Gets a collection of all actions. (Inherited from [DriveWorks.GroupMaintenance.CopyGroupProcess](topic9776.md))  
Public Method| [Start](topic9790.md)| Starts the process of copying a group. (Inherited from [DriveWorks.GroupMaintenance.CopyGroupProcess](topic9776.md))  
Public Method| [StopCopy](topic9791.md)| Stops the process from executing (if it was). (Inherited from [DriveWorks.GroupMaintenance.CopyGroupProcess](topic9776.md))  
Top

# Protected Methods

| Name| Description  
---|---|---  
Protected Method| [GetTargetPath](topic9788.md)|  (Inherited from [DriveWorks.GroupMaintenance.CopyGroupProcess](topic9776.md))  
Protected Method| [PlanActions](topic9934.md)| Overridden.   
Top

# Public Events

| Name| Description  
---|---|---  
![Public Event](dotnetimages/publicEvent.gif)| [StatusMessage](topic9796.md)| Raised whenever there is a status message event from the process. (Inherited from [DriveWorks.GroupMaintenance.CopyGroupProcess](topic9776.md))  
Top

# See Also

#### Reference

[PackageGroupProcess Class](topic9925.md)   
[DriveWorks.GroupMaintenance Namespace](topic9628.md)


