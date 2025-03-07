SetIsExtended Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Forms.DataModel Namespace](topic9371.md) > [DynamicProperty Class](topic9398.md) : SetIsExtended Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_control_
    The control on which to set the store name for the property.

_isExtended_
    True if the property should be extended, otherwise false.

Glossary Item Box

Sets whether the property is extended on the given control. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Sub SetIsExtended( _
       ByVal _control_ As [ControlBase](topic7698.md), _
       ByVal _isExtended_ As Boolean _
    )   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [DynamicProperty](topic9398.md)
    Dim control As [ControlBase](topic7698.md)
    Dim isExtended As Boolean
     
    instance.SetIsExtended(control, isExtended)  
  
C#|   
---|---  
      
    
    public void SetIsExtended( 
       [ControlBase](topic7698.md) _control_ ,
       bool _isExtended_
    )  
  
#### Parameters

 _control_
    The control on which to set the store name for the property.
_isExtended_
    True if the property should be extended, otherwise false.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[DynamicProperty Class](topic9398.md)   
[DynamicProperty Members](topic9399.md)


