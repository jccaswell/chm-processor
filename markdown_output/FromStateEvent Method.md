Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
FromStateEvent Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Transactions Namespace](topic12835.md) > [TaskSequenceRef Class](topic13159.md) : FromStateEvent Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_state_
    The state to which the event belongs.

_flowEvent_
    The event.

Glossary Item Box

Constructs a task sequence reference for the given event on the given state. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Shared Function FromStateEvent( _
       ByVal _state_ As [State](topic11559.md), _
       ByVal _flowEvent_ As [FlowEvent](topic10897.md) _
    ) As [TaskSequenceRef](topic13159.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim state As [State](topic11559.md)
    Dim flowEvent As [FlowEvent](topic10897.md)
    Dim value As [TaskSequenceRef](topic13159.md)
     
    value = [TaskSequenceRef](topic13159.md).FromStateEvent(state, flowEvent)  
  
C#|   
---|---  
      
    
    public static [TaskSequenceRef](topic13159.md) FromStateEvent( 
       [State](topic11559.md) _state_ ,
       [FlowEvent](topic10897.md) _flowEvent_
    )  
  
#### Parameters

 _state_
    The state to which the event belongs.
_flowEvent_
    The event.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[TaskSequenceRef Class](topic13159.md)   
[TaskSequenceRef Members](topic13160.md)


