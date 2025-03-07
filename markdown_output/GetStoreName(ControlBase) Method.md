Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
GetStoreName(ControlBase) Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Forms.DataModel Namespace](topic9371.md) > [DynamicProperty Class](topic9398.md) > [GetStoreName Method](topic9415.md) : GetStoreName(ControlBase) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_control_
    The control for which to get the property's store name.

Glossary Item Box

Gets the store name for a dynamic extended property. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Overloads Function GetStoreName( _
       ByVal _control_ As [ControlBase](topic7698.md) _
    ) As String  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [DynamicProperty](topic9398.md)
    Dim control As [ControlBase](topic7698.md)
    Dim value As String
     
    value = instance.GetStoreName(control)  
  
C#|   
---|---  
      
    
    public string GetStoreName( 
       [ControlBase](topic7698.md) _control_
    )  
  
#### Parameters

 _control_
    The control for which to get the property's store name.

#### Return Value

The store name for the dynamic extended property on the given control.

# Exceptions

Exception| Description  
---|---  
System.ArgumentNullException| The control was not specified.  
[DriveWorks.NotInitializedException](topic3735.md)| The control isn't initialized.  
System.ArgumentOutOfRangeException| The property isn't supported for the specified control, or the property isn't a dynamic extended property.  
  
# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[DynamicProperty Class](topic9398.md)   
[DynamicProperty Members](topic9399.md)   
[Overload List](topic9415.md)


