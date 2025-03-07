Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
ProjectComponentSetEventHandler Delegate   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) : ProjectComponentSetEventHandler Delegate  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_sender_
    The source of the event.

_e_
    The event data.

Glossary Item Box

Represents the method that will handle the event raised when a component set is changed. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Delegate Sub ProjectComponentSetEventHandler( _
       ByVal _sender_ As Object, _
       ByVal _e_ As [ProjectComponentSetEventArgs](topic4125.md) _
    )   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As New [ProjectComponentSetEventHandler](topic5933.md)(AddressOf HandlerMethod)  
  
C#|   
---|---  
      
    
    public delegate void ProjectComponentSetEventHandler( 
       object _sender_ ,
       [ProjectComponentSetEventArgs](topic4125.md) _e_
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

[ProjectComponentSetEventHandler Members](topic5933.md)   
[DriveWorks Namespace](topic2159.md)


