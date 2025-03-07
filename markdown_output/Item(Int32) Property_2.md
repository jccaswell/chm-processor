Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
Item(Int32) Property   
  
[DriveWorks.SolidWorks Assembly](topic13342.md) > [DriveWorks.SolidWorks.Components Namespace](topic13925.md) > [ProjectFileFormatCollection Class](topic14579.md) > [Item Property](topic14587.md) : Item(Int32) Property  
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
      
    
    Public Overloads ReadOnly Property Item( _
       ByVal _index_ As Integer _
    ) As [ProjectFileFormatRuleCollection](topic14603.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ProjectFileFormatCollection](topic14579.md)
    Dim index As Integer
    Dim value As [ProjectFileFormatRuleCollection](topic14603.md)
     
    value = instance.Item(index)  
  
C#|   
---|---  
      
    
    public [ProjectFileFormatRuleCollection](topic14603.md) Item( 
       int _index_
    ) {get;}  
  
#### Parameters

 _index_
    The index of the item to retrieve.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ProjectFileFormatCollection Class](topic14579.md)   
[ProjectFileFormatCollection Members](topic14580.md)   
[Overload List](topic14587.md)


