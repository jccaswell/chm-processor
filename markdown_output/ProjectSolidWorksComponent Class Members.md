Collapse All Expand All Members Options: Show All  Members Options: Filtered   
---  
DriveWorks SDK Documentation  |   
---|---  
ProjectSolidWorksComponent Class Members   
See Also Properties Methods Events [Send Feedback](mailto:apisupport@driveworks.co.uk?subject=Documentation Feedback: topic14692.md)  
[DriveWorks.SolidWorks Assembly](topic13342.md) > [DriveWorks.SolidWorks.Components Namespace](topic13925.md) : ProjectSolidWorksComponent Class  
---  
  
Include Inherited Members    
Include Protected Members  


Glossary Item Box

The following tables list the members exposed by [ProjectSolidWorksComponent](topic14692.md).

# Public Properties

| Name| Description  
---|---|---  
![Public Property](dotnetimages/publicProperty.gif)| [CapturedComponentId](topic14698.md)| Gets the unique identifier of the captured component to which the project component refers.   
![Public Property](dotnetimages/publicProperty.gif)| [FileName](topic14699.md)| Provides access to the file name rule and comment.   
![Public Property](dotnetimages/publicProperty.gif)| [IncludeFileFormatsInLoop](topic6192.md)| Gets/sets whether file formats should be generated in the loop. (Inherited from [DriveWorks.Components.ProjectComponent](topic6183.md))  
![Public Property](dotnetimages/publicProperty.gif)| [IsLoopEnabled](topic6193.md)| Gets/sets whether looping is enabled for this component. (Inherited from [DriveWorks.Components.ProjectComponent](topic6183.md))  
![Public Property](dotnetimages/publicProperty.gif)| [LoopCount](topic6194.md)| Gets the rule that controls how many times this component should be looped during release. (Inherited from [DriveWorks.Components.ProjectComponent](topic6183.md))  
![Public Property](dotnetimages/publicProperty.gif)| [MasterPath](topic14700.md)| Gets the master path for the component if the capture data is resolved, otherwise throws an exception.   
![Public Property](dotnetimages/publicProperty.gif)| [RelativePath](topic14701.md)| Provides access to the relative path rule and comment.   
![Public Property](dotnetimages/publicProperty.gif)| [Tasks](topic6195.md)| Gets the tasks associated with this component. (Inherited from [DriveWorks.Components.ProjectComponent](topic6183.md))  
Top

# Protected Properties

| Name| Description  
---|---|---  
![Protected Property](dotnetimages/protectedProperty.gif)| [Scopes](topic14702.md)| Overridden.   
Top

# Public Methods

| Name| Description  
---|---|---  
Public Method| CreateObjRef|  (Inherited from System.MarshalByRefObject)  
Public Method| GetLifetimeService|  (Inherited from System.MarshalByRefObject)  
Top

# Protected Methods

| Name| Description  
---|---|---  
Protected Method| [Initialize](topic6189.md)| When overridden by a derived class, performs any required initialization (Inherited from [DriveWorks.Components.ProjectComponent](topic6183.md))  
Protected Method| MemberwiseClone| Overloaded. (Inherited from System.MarshalByRefObject)  
Protected Method| [RaiseIsLoopChanged](topic6190.md)|  (Inherited from [DriveWorks.Components.ProjectComponent](topic6183.md))  
Protected Method| [RaiseLoopFileFormatsChanged](topic6191.md)|  (Inherited from [DriveWorks.Components.ProjectComponent](topic6183.md))  
Top

# Public Events

| Name| Description  
---|---|---  
![Public Event](dotnetimages/publicEvent.gif)| [IncludeFileFormatsInLoopChanged](topic6196.md)| Raised whenever the [DriveWorks.Components.ProjectComponent.IncludeFileFormatsInLoop](topic6192.md) property changes. (Inherited from [DriveWorks.Components.ProjectComponent](topic6183.md))  
![Public Event](dotnetimages/publicEvent.gif)| [IsLoopEnabledChanged](topic6197.md)| Raised whenever the [DriveWorks.Components.ProjectComponent.IsLoopEnabled](topic6193.md) property changes. (Inherited from [DriveWorks.Components.ProjectComponent](topic6183.md))  
Top

# See Also

#### Reference

[ProjectSolidWorksComponent Class](topic14692.md)   
[DriveWorks.SolidWorks.Components Namespace](topic13925.md)


