Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
GetStoreName(String) Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Forms.DataModel Namespace](topic9371.md) > [DynamicProperty Class](topic9398.md) > [GetStoreName Method](topic9415.md) : GetStoreName(String) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_controlName_
    The name of the control for which to get the property's store name.

Glossary Item Box

Gets the store name for a dynamic extended property. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Overloads Function GetStoreName( _
       ByVal _controlName_ As String _
    ) As String  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [DynamicProperty](topic9398.md)
    Dim controlName As String
    Dim value As String
     
    value = instance.GetStoreName(controlName)  
  
C#|   
---|---  
      
    
    public string GetStoreName( 
       string _controlName_
    )  
  
#### Parameters

 _controlName_
    The name of the control for which to get the property's store name.

#### Return Value

The store name for the dynamic extended property on the given control.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[DynamicProperty Class](topic9398.md)   
[DynamicProperty Members](topic9399.md)   
[Overload List](topic9415.md)


