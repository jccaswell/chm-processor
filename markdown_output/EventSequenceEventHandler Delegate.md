Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
EventSequenceEventHandler Delegate   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Specification Namespace](topic10764.md) : EventSequenceEventHandler Delegate  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_sender_
    The sender of the event.

_e_
    The event data.

Glossary Item Box

Represents a method which will handle an event sequence event. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Delegate Sub EventSequenceEventHandler( _
       ByVal _sender_ As Object, _
       ByVal _e_ As [EventSequenceEventArgs](topic10886.md) _
    )   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As New [EventSequenceEventHandler](topic11819.md)(AddressOf HandlerMethod)  
  
C#|   
---|---  
      
    
    public delegate void EventSequenceEventHandler( 
       object _sender_ ,
       [EventSequenceEventArgs](topic10886.md) _e_
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

[EventSequenceEventHandler Members](topic11819.md)   
[DriveWorks.Specification Namespace](topic10764.md)


