StopAutopilotTask Class   
[Members](topic12677.md)   
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Specification.StandardTasks Namespace](topic11896.md) : StopAutopilotTask Class  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Provides a task to request an Autopilot agent to stop. 

# Object Model

![](dotnetdiagramimages/image689.png)

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    <[TaskAttribute](topic11659.md)(DisplayName="resx://DriveWorks.TasksLocalizedResources,StopAutopilotTask", 
       Image="embedded://DriveWorks.AutopilotStopPlain16.png", 
       CategoryName="resx://DriveWorks.TasksLocalizedResources,TaskCategoryAutopilot", 
       WarningOutputEnabled=True)>
    Public Class StopAutopilotTask 
       Inherits [DriveWorks.Specification.Task](topic11629.md)
       Implements [DriveWorks.EventFlow.IFlowNode](topic6873.md), [DriveWorks.Extensibility.IExtension](topic7152.md)   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [StopAutopilotTask](topic12676.md)  
  
C#|   
---|---  
      
    
    [[TaskAttribute](topic11659.md)(DisplayName="resx://DriveWorks.TasksLocalizedResources,StopAutopilotTask", 
       Image="embedded://DriveWorks.AutopilotStopPlain16.png", 
       CategoryName="resx://DriveWorks.TasksLocalizedResources,TaskCategoryAutopilot", 
       WarningOutputEnabled=true)]
    public class StopAutopilotTask : [DriveWorks.Specification.Task](topic11629.md), [DriveWorks.EventFlow.IFlowNode](topic6873.md), [DriveWorks.Extensibility.IExtension](topic7152.md)    
  
# Inheritance Hierarchy

System.Object  
System.MarshalByRefObject  
[DriveWorks.EventFlow.ExecutableNodeBase](topic6938.md)  
[DriveWorks.EventFlow.ExecutableNodeWithStatus](topic6990.md)  
[DriveWorks.Specification.Task](topic11629.md)  
**DriveWorks.Specification.StandardTasks.StopAutopilotTask**  


# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[StopAutopilotTask Members](topic12677.md)   
[DriveWorks.Specification.StandardTasks Namespace](topic11896.md)


