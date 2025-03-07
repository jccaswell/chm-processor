Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
ConstantChangedEventHandler Delegate   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) : ConstantChangedEventHandler Delegate  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_sender_
    The source of the event.

_e_
    The event data.

Glossary Item Box

Represents the method that will handle the event raised when a constant is changed. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Delegate Sub ConstantChangedEventHandler( _
       ByVal _sender_ As Object, _
       ByVal _e_ As [ConstantEventArgs](topic2595.md) _
    )   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As New [ConstantChangedEventHandler](topic5929.md)(AddressOf HandlerMethod)  
  
C#|   
---|---  
      
    
    public delegate void ConstantChangedEventHandler( 
       object _sender_ ,
       [ConstantEventArgs](topic2595.md) _e_
    )  
  
#### Parameters

 _sender_
    The source of the event.
_e_
    The event data.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ConstantChangedEventHandler Members](topic5929.md)   
[DriveWorks Namespace](topic2159.md)


