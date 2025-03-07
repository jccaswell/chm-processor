Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
LeftChanged Event   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.EventFlow Namespace](topic6871.md) > [IFlowNode Interface](topic6873.md) : LeftChanged Event  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Occurs when the value of the [Left](topic6881.md) property has changed. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Event LeftChanged As EventHandler(Of EventArgs)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [IFlowNode](topic6873.md)
    Dim handler As EventHandler(Of EventArgs)
     
    AddHandler instance.LeftChanged, handler  
  
C#|   
---|---  
      
    
    event EventHandler<EventArgs> LeftChanged  
  
# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[IFlowNode Interface](topic6873.md)   
[IFlowNode Members](topic6874.md)


