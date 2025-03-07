Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
GetReferenceByComponentSetName Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Components Namespace](topic6089.md) > [ReleaseComponentController Class](topic6252.md) : GetReferenceByComponentSetName Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_name_
    

Glossary Item Box

Gets the root component reference for the component set with the given name from the local release results. See remarks for details. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function GetReferenceByComponentSetName( _
       ByVal _name_ As String _
    ) As [ReadOnlyReleasedComponentReferenceDetails](topic6239.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ReleaseComponentController](topic6252.md)
    Dim name As String
    Dim value As [ReadOnlyReleasedComponentReferenceDetails](topic6239.md)
     
    value = instance.GetReferenceByComponentSetName(name)  
  
C#|   
---|---  
      
    
    public [ReadOnlyReleasedComponentReferenceDetails](topic6239.md) GetReferenceByComponentSetName( 
       string _name_
    )  
  
#### Parameters

 _name_
    

#### Return Value

The root component reference for the component set with the given name, or a null reference if no component set was found with the given name.

# Remarks

This method will return the results of evaluating the given component set, even if it was deleted/suppressed/an alternative/etc.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ReleaseComponentController Class](topic6252.md)   
[ReleaseComponentController Members](topic6253.md)


