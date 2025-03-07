Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
GetIsExtended Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Forms.DataModel Namespace](topic9371.md) > [DynamicProperty Class](topic9398.md) : GetIsExtended Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_control_
    The control to check whether this property is extended or not.

Glossary Item Box

Gets whether the property is extended on the given control. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function GetIsExtended( _
       ByVal _control_ As [ControlBase](topic7698.md) _
    ) As Boolean  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [DynamicProperty](topic9398.md)
    Dim control As [ControlBase](topic7698.md)
    Dim value As Boolean
     
    value = instance.GetIsExtended(control)  
  
C#|   
---|---  
      
    
    public bool GetIsExtended( 
       [ControlBase](topic7698.md) _control_
    )  
  
#### Parameters

 _control_
    The control to check whether this property is extended or not.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[DynamicProperty Class](topic9398.md)   
[DynamicProperty Members](topic9399.md)


