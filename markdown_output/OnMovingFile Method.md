Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
OnMovingFile Method   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications.Autopilot.Extensibility Namespace](topic1633.md) > [IAutopilotService Interface](topic1654.md) : OnMovingFile Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_sender_
    

_e_
    

Glossary Item Box

Raises the [MovingFile](topic1683.md) event. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Sub OnMovingFile( _
       ByVal _sender_ As Object, _
       ByRef _e_ As [MovingFileEventArgs](topic1888.md) _
    )   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [IAutopilotService](topic1654.md)
    Dim sender As Object
    Dim e As [MovingFileEventArgs](topic1888.md)
     
    instance.OnMovingFile(sender, e)  
  
C#|   
---|---  
      
    
    void OnMovingFile( 
       object _sender_ ,
       ref [MovingFileEventArgs](topic1888.md) _e_
    )  
  
#### Parameters

 _sender_
    
_e_
    

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[IAutopilotService Interface](topic1654.md)   
[IAutopilotService Members](topic1655.md)


