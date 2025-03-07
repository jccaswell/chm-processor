Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
CreatingControl Event   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Forms Namespace](topic7266.md) > [Form Class](topic8086.md) : CreatingControl Event  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Raised when a control is being created. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Event CreatingControl As EventHandler(Of CreatingControlEventArgs)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [Form](topic8086.md)
    Dim handler As EventHandler(Of CreatingControlEventArgs)
     
    AddHandler instance.CreatingControl, handler  
  
C#|   
---|---  
      
    
    public event EventHandler<CreatingControlEventArgs> CreatingControl  
  
# Event Data

The event handler receives an argument of type [CreatingControlEventArgs](topic7826.md) containing data related to this event. The following **CreatingControlEventArgs** properties provide information specific to this event.

Property| Description  
---|---  
[Cancel](topic7835.md)| Whether or not the creation of the control will be cancelled.   
[ControlName](topic7836.md)| The name of the control that is being created.   
[ControlType](topic7837.md)| The type of control that is being created.   
  
# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[Form Class](topic8086.md)   
[Form Members](topic8087.md)


