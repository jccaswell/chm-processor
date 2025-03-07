Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
CreateProject Method   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications Namespace](topic16.md) > [IProjectService Interface](topic382.md) : CreateProject Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_group_
    The group in which to create the project.

_path_
    The fully qualified path to the new project file.

_additionalParameters_
    Optional additional parameters to pass to the project being created.

Glossary Item Box

Creates a new project. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Sub CreateProject( _
       ByVal _group_ As [Group](topic2958.md), _
       ByVal _path_ As String, _
       ByVal _additionalParameters_ As String _
    )   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [IProjectService](topic382.md)
    Dim group As [Group](topic2958.md)
    Dim path As String
    Dim additionalParameters As String
     
    instance.CreateProject(group, path, additionalParameters)  
  
C#|   
---|---  
      
    
    void CreateProject( 
       [Group](topic2958.md) _group_ ,
       string _path_ ,
       string _additionalParameters_
    )  
  
#### Parameters

 _group_
    The group in which to create the project.
_path_
    The fully qualified path to the new project file.
_additionalParameters_
    Optional additional parameters to pass to the project being created.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[IProjectService Interface](topic382.md)   
[IProjectService Members](topic383.md)


