Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
Add Method   
  
[DriveWorks.SolidWorks Assembly](topic13342.md) > [DriveWorks.SolidWorks.Components Namespace](topic13925.md) > [CapturedSheetCollection Class](topic14331.md) : Add Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_name_
    

Glossary Item Box

Adds a new sheet. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function Add( _
       ByVal _name_ As String _
    ) As [CapturedSheet](topic14323.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [CapturedSheetCollection](topic14331.md)
    Dim name As String
    Dim value As [CapturedSheet](topic14323.md)
     
    value = instance.Add(name)  
  
C#|   
---|---  
      
    
    public [CapturedSheet](topic14323.md) Add( 
       string _name_
    )  
  
#### Parameters

 _name_
    

#### Return Value

The newly created sheet.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[CapturedSheetCollection Class](topic14331.md)   
[CapturedSheetCollection Members](topic14332.md)


