Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
IDocumentDesigner Interface   
[Members](topic1518.md)   
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications.Administrator.Extensibility.Documents Namespace](topic1507.md) : IDocumentDesigner Interface  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Provides a contract for objects which provide support for creating and administering documents. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Interface IDocumentDesigner 
       Inherits [DriveWorks.Extensibility.IExtension](topic7152.md)   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [IDocumentDesigner](topic1517.md)  
  
C#|   
---|---  
      
    
    public interface IDocumentDesigner : [DriveWorks.Extensibility.IExtension](topic7152.md)    
  
# Remarks

To support test specification capabilities, the document designer should implement the [IDocumentTestProvider](topic1540.md) interface in addition to this interface.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[IDocumentDesigner Members](topic1518.md)   
[DriveWorks.Applications.Administrator.Extensibility.Documents Namespace](topic1507.md)


