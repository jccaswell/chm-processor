Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
Item Property   
  
[DriveWorks.SolidWorks Assembly](topic13342.md) > [DriveWorks.SolidWorks.Components Namespace](topic13925.md) > [CapturedDimensionCollection Class](topic14162.md) : Item Property  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_index_
    The index of the item to retrieve.

Glossary Item Box

Gets the item at the specified index. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public ReadOnly Default Property Item( _
       ByVal _index_ As Integer _
    ) As [CapturedDimension](topic14154.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [CapturedDimensionCollection](topic14162.md)
    Dim index As Integer
    Dim value As [CapturedDimension](topic14154.md)
     
    value = instance.Item(index)  
  
C#|   
---|---  
      
    
    public [CapturedDimension](topic14154.md) this[ 
       int _index_
    ]; {get;}  
  
#### Parameters

 _index_
    The index of the item to retrieve.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[CapturedDimensionCollection Class](topic14162.md)   
[CapturedDimensionCollection Members](topic14163.md)


