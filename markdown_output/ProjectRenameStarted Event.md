Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
ProjectRenameStarted Event   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications Namespace](topic16.md) > [IProjectService Interface](topic382.md) : ProjectRenameStarted Event  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Raised when a project has started the renaming process. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Event ProjectRenameStarted As EventHandler(Of ProjectRenameEventArgs)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [IProjectService](topic382.md)
    Dim handler As EventHandler(Of ProjectRenameEventArgs)
     
    AddHandler instance.ProjectRenameStarted, handler  
  
C#|   
---|---  
      
    
    event EventHandler<ProjectRenameEventArgs> ProjectRenameStarted  
  
# Event Data

The event handler receives an argument of type [ProjectRenameEventArgs](topic907.md) containing data related to this event. The following **ProjectRenameEventArgs** properties provide information specific to this event.

Property| Description  
---|---  
[ProjectDetails](topic914.md)| Gets the [ProjectDetails](topic914.md) of the project that is opening.   
  
# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[IProjectService Interface](topic382.md)   
[IProjectService Members](topic383.md)


