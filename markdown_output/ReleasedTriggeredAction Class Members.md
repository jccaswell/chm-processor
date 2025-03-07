ReleasedTriggeredAction Class Members   
See Also Properties Methods [Send Feedback](mailto:apisupport@driveworks.co.uk?subject=Documentation Feedback: topic5123.md)  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) : ReleasedTriggeredAction Class  
---  
  
Include Inherited Members    
Include Protected Members  


Glossary Item Box

The following tables list the members exposed by [ReleasedTriggeredAction](topic5123.md).

# Public Constructors

| Name| Description  
---|---|---  
![Public Constructor](dotnetimages/publicConstructor.gif)| [ReleasedTriggeredAction Constructor](topic5129.md)| Initializes a new [ReleasedTriggeredAction](topic5123.md) with empty values.   
Top

# Public Properties

| Name| Description  
---|---|---  
![Public Property](dotnetimages/publicProperty.gif)| [Action](topic5135.md)| Gets/sets the name of the operation or transition to run.   
![Public Property](dotnetimages/publicProperty.gif)| [Element](topic5136.md)| Gets the XML element of the triggered action.   
![Public Property](dotnetimages/publicProperty.gif)| [FailedCount](topic5137.md)| Gets the amount of times that the triggered action has failed to execute.   
![Public Property](dotnetimages/publicProperty.gif)| [FailureMessages](topic5138.md)| Gets information regarding failed attempts at executing the triggered action.   
![Public Property](dotnetimages/publicProperty.gif)| [FilePaths](topic5139.md)| Gets an array of file paths that the triggered action is waiting for.   
![Public Property](dotnetimages/publicProperty.gif)| [FilePathsDisplayValue](topic5140.md)| Gets/sets the pipe delimited string of the file paths that the triggered action is waiting for.   
![Public Property](dotnetimages/publicProperty.gif)| [Name](topic5141.md)| Gets/sets the Name of the triggered action document.   
![Public Property](dotnetimages/publicProperty.gif)| [StatesToTriggerOn](topic5142.md)| Gets/sets the states that this action should be triggered on.   
![Public Property](dotnetimages/publicProperty.gif)| [StatesToTriggerOnDisplayValue](topic5143.md)| Gets the states that this action should be triggered on.   
![Public Property](dotnetimages/publicProperty.gif)| [Task](topic5144.md)| Gets the task information associated with this triggered action.   
Top

# Public Methods

| Name| Description  
---|---|---  
Public Method| [AddFailMessage](topic5130.md)| Add a failure to the [FailureMessages](topic5138.md) list.   
Public Method| [ClearFailures](topic5131.md)| Clears any failures associated with this triggered action.   
Public Method| [Load](topic5132.md)| Reads the information stored about the triggered action from the specified task.   
Public Method| [SynchronizeData](topic5133.md)| Synchronizes the XML for this triggered action with its specification task.   
Public Method| [UpdateFilePath](topic5134.md)| Updates the specified file path to the new location.   
Top

# See Also

#### Reference

[ReleasedTriggeredAction Class](topic5123.md)   
[DriveWorks Namespace](topic2159.md)


