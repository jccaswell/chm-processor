Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
GetComponentReferenceTree Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [GroupReleasedComponents Class](topic3238.md) : GetComponentReferenceTree Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_ids_
    The identifiers of the released components to traverse and return reference information.

Glossary Item Box

Gets hierarchical reference information about the components with the given identifiers. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function GetComponentReferenceTree( _
       ByVal ParamArray _ids_() As Guid _
    ) As [IReleasedComponentReferenceTree](topic6106.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [GroupReleasedComponents](topic3238.md)
    Dim ids() As Guid
    Dim value As [IReleasedComponentReferenceTree](topic6106.md)
     
    value = instance.GetComponentReferenceTree(ids)  
  
C#|   
---|---  
      
    
    public [IReleasedComponentReferenceTree](topic6106.md) GetComponentReferenceTree( 
       params Guid[] _ids_
    )  
  
#### Parameters

 _ids_
    The identifiers of the released components to traverse and return reference information.

#### Return Value

An instance of an object which implements the [DriveWorks.Components.IReleasedComponentReferenceTree](topic6106.md) interface.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[GroupReleasedComponents Class](topic3238.md)   
[GroupReleasedComponents Members](topic3239.md)


