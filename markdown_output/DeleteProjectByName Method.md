Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
DeleteProjectByName Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [GroupProjects Class](topic3190.md) : DeleteProjectByName Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_name_
    Name of the project to delete.

Glossary Item Box

Deletes an existing project using it's name. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function DeleteProjectByName( _
       ByVal _name_ As String _
    ) As Boolean  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [GroupProjects](topic3190.md)
    Dim name As String
    Dim value As Boolean
     
    value = instance.DeleteProjectByName(name)  
  
C#|   
---|---  
      
    
    public bool DeleteProjectByName( 
       string _name_
    )  
  
#### Parameters

 _name_
    Name of the project to delete.

#### Return Value

True if successfully deleted.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[GroupProjects Class](topic3190.md)   
[GroupProjects Members](topic3191.md)


