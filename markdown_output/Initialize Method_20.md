Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
Initialize Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [IHasProjectFunctions Interface](topic2231.md) : Initialize Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_project_
    The project that the functions are being loaded for.

Glossary Item Box

Performs initialization logic. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Sub Initialize( _
       ByVal _project_ As [Project](topic3859.md) _
    )   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [IHasProjectFunctions](topic2231.md)
    Dim project As [Project](topic3859.md)
     
    instance.Initialize(project)  
  
C#|   
---|---  
      
    
    void Initialize( 
       [Project](topic3859.md) _project_
    )  
  
#### Parameters

 _project_
    The project that the functions are being loaded for.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[IHasProjectFunctions Interface](topic2231.md)   
[IHasProjectFunctions Members](topic2232.md)


