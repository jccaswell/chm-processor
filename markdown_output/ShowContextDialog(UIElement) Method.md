ShowContextDialog(UIElement) Method   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications Namespace](topic16.md) > [ICommandButton Interface](topic115.md) > [ShowContextDialog Method](topic120.md) : ShowContextDialog(UIElement) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_control_
    The WPF control to show in the contextual dialog.

Glossary Item Box

Shows a contextual dialog next to the button that can be used to take input from the user. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Overloads Sub ShowContextDialog( _
       ByVal _control_ As UIElement _
    )   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ICommandButton](topic115.md)
    Dim control As UIElement
     
    instance.ShowContextDialog(control)  
  
C#|   
---|---  
      
    
    void ShowContextDialog( 
       UIElement _control_
    )  
  
#### Parameters

 _control_
    The WPF control to show in the contextual dialog.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ICommandButton Interface](topic115.md)   
[ICommandButton Members](topic116.md)   
[Overload List](topic120.md)


