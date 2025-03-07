Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
IsValid Method   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications.Extensibility Namespace](topic1995.md) > [IProjectTemplateHelper Interface](topic2091.md) : IsValid Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_application_
    The DriveWorks application.

Glossary Item Box

Indicates whether the current template is valid for this application. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Function IsValid( _
       ByVal _application_ As [IApplication](topic24.md) _
    ) As Boolean  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [IProjectTemplateHelper](topic2091.md)
    Dim application As [IApplication](topic24.md)
    Dim value As Boolean
     
    value = instance.IsValid(application)  
  
C#|   
---|---  
      
    
    bool IsValid( 
       [IApplication](topic24.md) _application_
    )  
  
#### Parameters

 _application_
    The DriveWorks application.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[IProjectTemplateHelper Interface](topic2091.md)   
[IProjectTemplateHelper Members](topic2092.md)


