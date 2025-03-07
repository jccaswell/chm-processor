Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
IsCompatible Method   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications.Administrator.Extensibility.Documents Namespace](topic1507.md) > [IDocumentDesigner Interface](topic1517.md) : IsCompatible Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_application_
    The running application.

Glossary Item Box

Queries the designer to see if it is compatible with the current application and it's design master etc. If this value returns false then the document will not be visible as a new document type. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Function IsCompatible( _
       ByVal _application_ As [IApplication](topic24.md) _
    ) As Boolean  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [IDocumentDesigner](topic1517.md)
    Dim application As [IApplication](topic24.md)
    Dim value As Boolean
     
    value = instance.IsCompatible(application)  
  
C#|   
---|---  
      
    
    bool IsCompatible( 
       [IApplication](topic24.md) _application_
    )  
  
#### Parameters

 _application_
    The running application.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[IDocumentDesigner Interface](topic1517.md)   
[IDocumentDesigner Members](topic1518.md)


