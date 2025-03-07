Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
FindIndex Method   
  
[DriveWorks.SolidWorks Assembly](topic13342.md) > [DriveWorks.SolidWorks.Components Namespace](topic13925.md) > [CapturedFormatCollection Class](topic14249.md) : FindIndex Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_name_
    The name to find.

Glossary Item Box

Finds the file format with the given name. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function FindIndex( _
       ByVal _name_ As String _
    ) As Integer  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [CapturedFormatCollection](topic14249.md)
    Dim name As String
    Dim value As Integer
     
    value = instance.FindIndex(name)  
  
C#|   
---|---  
      
    
    public int FindIndex( 
       string _name_
    )  
  
#### Parameters

 _name_
    The name to find.

#### Return Value

-1 if the item isn't found, otherwise the index of the item.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[CapturedFormatCollection Class](topic14249.md)   
[CapturedFormatCollection Members](topic14250.md)


