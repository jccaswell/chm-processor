Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
Added Event   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Components.Tasks Namespace](topic6391.md) > [ComponentTaskReleaseConditions Class](topic6682.md) : Added Event  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

The event that gets raised whenever a task has been added to the collection. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Event Added As EventHandler(Of ComponentTaskReleaseConditionEventArgs)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ComponentTaskReleaseConditions](topic6682.md)
    Dim handler As EventHandler(Of ComponentTaskReleaseConditionEventArgs)
     
    AddHandler instance.Added, handler  
  
C#|   
---|---  
      
    
    public event EventHandler<ComponentTaskReleaseConditionEventArgs> Added  
  
# Event Data

The event handler receives an argument of type [ComponentTaskReleaseConditionEventArgs](topic6663.md) containing data related to this event. The following **ComponentTaskReleaseConditionEventArgs** properties provide information specific to this event.

Property| Description  
---|---  
[Condition](topic6669.md)| Gets the condition involved in the event.   
  
# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ComponentTaskReleaseConditions Class](topic6682.md)   
[ComponentTaskReleaseConditions Members](topic6683.md)


