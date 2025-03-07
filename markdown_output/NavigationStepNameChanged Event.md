Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
NavigationStepNameChanged Event   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Navigation Namespace](topic10114.md) > [ProjectNavigation Class](topic10222.md) : NavigationStepNameChanged Event  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Raised when the name of a navigation step is changed. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Event NavigationStepNameChanged As [NavigationStepNameChangedEventHandler](topic10265.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ProjectNavigation](topic10222.md)
    Dim handler As [NavigationStepNameChangedEventHandler](topic10265.md)
     
    AddHandler instance.NavigationStepNameChanged, handler  
  
C#|   
---|---  
      
    
    public event [NavigationStepNameChangedEventHandler](topic10265.md) NavigationStepNameChanged  
  
# Event Data

The event handler receives an argument of type [NavigationStepNameChangedEventArgs](topic10213.md) containing data related to this event. The following **NavigationStepNameChangedEventArgs** properties provide information specific to this event.

Property| Description  
---|---  
[NavigationStep](topic10212.md)| Gets the navigation step that was changed. (Inherited from [DriveWorks.Navigation.NavigationStepEventArgs](topic10205.md))  
[NewName](topic10220.md)| Gets the new name of the navigation step.   
[OldName](topic10221.md)| Gets the old name of the navigation step.   
  
# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ProjectNavigation Class](topic10222.md)   
[ProjectNavigation Members](topic10223.md)


