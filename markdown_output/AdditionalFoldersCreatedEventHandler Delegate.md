Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
AdditionalFoldersCreatedEventHandler Delegate   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Specification Namespace](topic10764.md) : AdditionalFoldersCreatedEventHandler Delegate  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_sender_
    The sender of the event.

_e_
    The event data.

Glossary Item Box

Represents a method which will handle the creation of additional folders. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Delegate Sub AdditionalFoldersCreatedEventHandler( _
       ByVal _sender_ As Object, _
       ByVal _e_ As [AdditionalFoldersCreatedEventArgs](topic10775.md) _
    )   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As New [AdditionalFoldersCreatedEventHandler](topic11817.md)(AddressOf HandlerMethod)  
  
C#|   
---|---  
      
    
    public delegate void AdditionalFoldersCreatedEventHandler( 
       object _sender_ ,
       [AdditionalFoldersCreatedEventArgs](topic10775.md) _e_
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

[AdditionalFoldersCreatedEventHandler Members](topic11817.md)   
[DriveWorks.Specification Namespace](topic10764.md)


