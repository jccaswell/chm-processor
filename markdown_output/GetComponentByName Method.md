Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
GetComponentByName Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Components Namespace](topic6089.md) > [ReleaseComponentController Class](topic6252.md) : GetComponentByName Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_name_
    The name of the component to retrieve.

Glossary Item Box

Gets a component with the given name from the local release results. See remarks for details. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function GetComponentByName( _
       ByVal _name_ As String _
    ) As [ReleasedComponent](topic6324.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ReleaseComponentController](topic6252.md)
    Dim name As String
    Dim value As [ReleasedComponent](topic6324.md)
     
    value = instance.GetComponentByName(name)  
  
C#|   
---|---  
      
    
    public [ReleasedComponent](topic6324.md) GetComponentByName( 
       string _name_
    )  
  
#### Parameters

 _name_
    The name of the component to retrieve.

#### Return Value

The component with the given name, or a null reference if no component was found with the given name.

# Remarks

This method looks for a component with the given name in the release results, but does not search against the group.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ReleaseComponentController Class](topic6252.md)   
[ReleaseComponentController Members](topic6253.md)


