Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
GetExtensibilityAttributes() Method   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications.Extensibility Namespace](topic1995.md) > [ILibraryInfo Interface](topic2055.md) > [GetExtensibilityAttributes Method](topic2060.md) : GetExtensibilityAttributes() Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Gets the extensibility attributes for the library. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Overloads Function GetExtensibilityAttributes() As [ExtensibilityAttribute()](topic7177.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ILibraryInfo](topic2055.md)
    Dim value() As [ExtensibilityAttribute](topic7177.md)
     
    value = instance.GetExtensibilityAttributes()  
  
C#|   
---|---  
      
    
    [ExtensibilityAttribute[]](topic7177.md) GetExtensibilityAttributes()  
  
# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ILibraryInfo Interface](topic2055.md)   
[ILibraryInfo Members](topic2056.md)   
[Overload List](topic2060.md)


