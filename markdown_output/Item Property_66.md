Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
Item Property   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Forms Namespace](topic7266.md) > [ControlCollection Class](topic7766.md) : Item Property  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_index_
    The index of the item to retrieve.

Glossary Item Box

Gets the control at the given index. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public ReadOnly Default Property Item( _
       ByVal _index_ As Integer _
    ) As [ControlBase](topic7698.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ControlCollection](topic7766.md)
    Dim index As Integer
    Dim value As [ControlBase](topic7698.md)
     
    value = instance.Item(index)  
  
C#|   
---|---  
      
    
    public [ControlBase](topic7698.md) this[ 
       int _index_
    ]; {get;}  
  
#### Parameters

 _index_
    The index of the item to retrieve.

#### Property Value

The item at the specified index.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ControlCollection Class](topic7766.md)   
[ControlCollection Members](topic7767.md)


