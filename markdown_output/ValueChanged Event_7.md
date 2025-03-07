ValueChanged Event   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Forms Namespace](topic7266.md) > [ControlBase Class](topic7698.md) : ValueChanged Event  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Raised when the value of a property on the control changes. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Event ValueChanged As [ValueChangedEventHandler](topic9590.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ControlBase](topic7698.md)
    Dim handler As [ValueChangedEventHandler](topic9590.md)
     
    AddHandler instance.ValueChanged, handler  
  
C#|   
---|---  
      
    
    public event [ValueChangedEventHandler](topic9590.md) ValueChanged  
  
# Event Data

The event handler receives an argument of type [ValueChangedEventArgs](topic9575.md) containing data related to this event. The following **ValueChangedEventArgs** properties provide information specific to this event.

Property| Description  
---|---  
[EventArgument](topic9584.md)| Gets the argument describing the source of this change.   
[NewValue](topic9585.md)| Gets the value of the property as it after the change.   
[OldValue](topic9586.md)| Gets the value of the property as it was before the change.   
[Property](topic9587.md)| Gets the property that was changed.   
  
# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ControlBase Class](topic7698.md)   
[ControlBase Members](topic7699.md)


