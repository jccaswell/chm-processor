Collapse All Expand All Members Options: Show All  Members Options: Filtered   
---  
DriveWorks SDK Documentation  |   
---|---  
ComponentTaskAccessor Class Members   
See Also Properties Methods [Send Feedback](mailto:apisupport@driveworks.co.uk?subject=Documentation Feedback: topic6429.md)  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Components.Tasks Namespace](topic6391.md) : ComponentTaskAccessor Class  
---  
  
Include Inherited Members    
Include Protected Members  


Glossary Item Box

The following tables list the members exposed by [ComponentTaskAccessor](topic6429.md).

# Public Properties

| Name| Description  
---|---|---  
![Public Property](dotnetimages/publicProperty.gif)| [Item](topic6453.md)| Gets the [ComponentTaskCollection](topic6466.md) for the tasks with the specified location.   
![Public Property](dotnetimages/publicProperty.gif)| [TotalTaskCount](topic6454.md)| Gets the total number of tasks in the accessor.   
Top

# Protected Properties

| Name| Description  
---|---|---  
![Protected Property](dotnetimages/protectedProperty.gif)| [Collections](topic6452.md)| Gets the task collections this accessor manages.   
Top

# Public Methods

| Name| Description  
---|---|---  
Public Method| [Add](topic6435.md)| Overloaded. Adds a new task to the collection and returns the newly created task.   
Public Method| [Clear](topic6440.md)| Removes all tasks managed by this accessor from the project.   
Public Method| [Get](topic6442.md)| Overloaded. Gets the task with the given id in the collection (or a null reference if the task doesn't exist).   
Public Method| [Insert](topic6445.md)| Overloaded. Creates and inserts a new [ComponentTask](topic6407.md) at the given index.   
Public Method| [IsNameTaken](topic6450.md)| Checks if the given name is occupied by a task in any of the collections managed by this accessor.   
Public Method| [Remove](topic6451.md)| Removes the given task from the collection and deletes it from the project.   
Top

# Protected Methods

| Name| Description  
---|---|---  
Protected Method| [EnsureCollection](topic6441.md)| Ensures that a task collection for the given location has been created.   
Top

# See Also

#### Reference

[ComponentTaskAccessor Class](topic6429.md)   
[DriveWorks.Components.Tasks Namespace](topic6391.md)


