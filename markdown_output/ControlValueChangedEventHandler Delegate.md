Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
ControlValueChangedEventHandler Delegate   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Forms.DataModel Namespace](topic9371.md) : ControlValueChangedEventHandler Delegate  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_sender_
    The sender of the event.

_e_
    The event data.

Glossary Item Box

Represents the method that will handle a control value changed event. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Delegate Sub ControlValueChangedEventHandler( _
       ByVal _sender_ As Object, _
       ByVal _e_ As [ControlValueChangedEventArgs](topic9385.md) _
    )   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As New [ControlValueChangedEventHandler](topic9588.md)(AddressOf HandlerMethod)  
  
C#|   
---|---  
      
    
    public delegate void ControlValueChangedEventHandler( 
       object _sender_ ,
       [ControlValueChangedEventArgs](topic9385.md) _e_
    )  
  
#### Parameters

 _sender_
    The sender of the event.
_e_
    The event data.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ControlValueChangedEventHandler Members](topic9588.md)   
[DriveWorks.Forms.DataModel Namespace](topic9371.md)


