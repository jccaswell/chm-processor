Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
Add Method   
  
[DriveWorks.SolidWorks Assembly](topic13342.md) > [DriveWorks.SolidWorks.Components Namespace](topic13925.md) > [CapturedCustomPropertyCollection Class](topic14139.md) : Add Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_name_
    The name of the custom property.

Glossary Item Box

Adds and returns a new custom property with the given name. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function Add( _
       ByVal _name_ As String _
    ) As [CapturedCustomProperty](topic14132.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [CapturedCustomPropertyCollection](topic14139.md)
    Dim name As String
    Dim value As [CapturedCustomProperty](topic14132.md)
     
    value = instance.Add(name)  
  
C#|   
---|---  
      
    
    public [CapturedCustomProperty](topic14132.md) Add( 
       string _name_
    )  
  
#### Parameters

 _name_
    The name of the custom property.

#### Return Value

The newly added custom property.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[CapturedCustomPropertyCollection Class](topic14139.md)   
[CapturedCustomPropertyCollection Members](topic14140.md)


