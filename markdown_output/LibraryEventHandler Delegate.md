Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
LibraryEventHandler Delegate   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications.Extensibility Namespace](topic1995.md) : LibraryEventHandler Delegate  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_sender_
    The sender of the event.

_e_
    The event data.

Glossary Item Box

Represents a method that will handle events for the [ILibraryManager](topic2079.md) class. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Delegate Sub LibraryEventHandler( _
       ByVal _sender_ As Object, _
       ByVal _e_ As [LibraryEventArgs](topic2124.md) _
    )   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As New [LibraryEventHandler](topic2155.md)(AddressOf HandlerMethod)  
  
C#|   
---|---  
      
    
    public delegate void LibraryEventHandler( 
       object _sender_ ,
       [LibraryEventArgs](topic2124.md) _e_
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

[LibraryEventHandler Members](topic2155.md)   
[DriveWorks.Applications.Extensibility Namespace](topic1995.md)


