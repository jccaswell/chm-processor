Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
Item Property   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Specification Namespace](topic10764.md) > [States Class](topic11612.md) : Item Property  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_index_
    The index of the item to get.

Glossary Item Box

Gets the item at the specified index. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public ReadOnly Default Property Item( _
       ByVal _index_ As Integer _
    ) As [State](topic11559.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [States](topic11612.md)
    Dim index As Integer
    Dim value As [State](topic11559.md)
     
    value = instance.Item(index)  
  
C#|   
---|---  
      
    
    public [State](topic11559.md) this[ 
       int _index_
    ]; {get;}  
  
#### Parameters

 _index_
    The index of the item to get.

# Exceptions

Exception| Description  
---|---  
System.ArgumentOutOfRangeException| The specified index was out of the range of the collection.  
  
# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[States Class](topic11612.md)   
[States Members](topic11613.md)


