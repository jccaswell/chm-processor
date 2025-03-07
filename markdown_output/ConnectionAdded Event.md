Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
ConnectionAdded Event   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.EventFlow Namespace](topic6871.md) > [InputConnectionEndpoint Class](topic7033.md) : ConnectionAdded Event  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Occurs when a connection has been added to this input. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Event ConnectionAdded As EventHandler(Of ConnectionEventArgs)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [InputConnectionEndpoint](topic7033.md)
    Dim handler As EventHandler(Of ConnectionEventArgs)
     
    AddHandler instance.ConnectionAdded, handler  
  
C#|   
---|---  
      
    
    public event EventHandler<ConnectionEventArgs> ConnectionAdded  
  
# Event Data

The event handler receives an argument of type [ConnectionEventArgs](topic6930.md) containing data related to this event. The following **ConnectionEventArgs** properties provide information specific to this event.

Property| Description  
---|---  
[Connection](topic6937.md)| The [Connection](topic6909.md) for the event.   
  
# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[InputConnectionEndpoint Class](topic7033.md)   
[InputConnectionEndpoint Members](topic7034.md)


