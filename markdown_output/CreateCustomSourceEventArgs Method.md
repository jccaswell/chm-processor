Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
CreateCustomSourceEventArgs Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [FormControlValueChangeEventArgs Class](topic2895.md) : CreateCustomSourceEventArgs Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_source_
    The source of the event.

Glossary Item Box

Initializes an instance of [FormControlValueChangeEventArgs](topic2895.md) with values describing a custom source. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Shared Function CreateCustomSourceEventArgs( _
       ByVal _source_ As String _
    ) As [FormControlValueChangeEventArgs](topic2895.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim source As String
    Dim value As [FormControlValueChangeEventArgs](topic2895.md)
     
    value = [FormControlValueChangeEventArgs](topic2895.md).CreateCustomSourceEventArgs(source)  
  
C#|   
---|---  
      
    
    public static [FormControlValueChangeEventArgs](topic2895.md) CreateCustomSourceEventArgs( 
       string _source_
    )  
  
#### Parameters

 _source_
    The source of the event.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[FormControlValueChangeEventArgs Class](topic2895.md)   
[FormControlValueChangeEventArgs Members](topic2896.md)


