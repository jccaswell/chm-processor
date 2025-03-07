Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
Item Property   
  
[DriveWorks.SolidWorks Assembly](topic13342.md) > [DriveWorks.SolidWorks.Components Namespace](topic13925.md) > [CapturedBreakLineCollection Class](topic14101.md) : Item Property  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_index_
    The index of the break-line to retrieve.

Glossary Item Box

Gets the break-line at the given index. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public ReadOnly Property Item( _
       ByVal _index_ As Integer _
    ) As [CapturedBreakLine](topic14094.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [CapturedBreakLineCollection](topic14101.md)
    Dim index As Integer
    Dim value As [CapturedBreakLine](topic14094.md)
     
    value = instance.Item(index)  
  
C#|   
---|---  
      
    
    public [CapturedBreakLine](topic14094.md) Item( 
       int _index_
    ) {get;}  
  
#### Parameters

 _index_
    The index of the break-line to retrieve.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[CapturedBreakLineCollection Class](topic14101.md)   
[CapturedBreakLineCollection Members](topic14102.md)


