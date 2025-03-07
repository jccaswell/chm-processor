Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
GetComponentDetailsById Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [GroupReleasedComponents Class](topic3238.md) : GetComponentDetailsById Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_componentId_
    The unique identifier of the component.

_throwIfMissing_
    Throws an exception if a component with the specified identiifer cannot be found, if false, a null reference is returned if the component isn't found.

Glossary Item Box

Get's the component details for a component with the specified identifier. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function GetComponentDetailsById( _
       ByVal _componentId_ As Guid, _
       ByVal _throwIfMissing_ As Boolean _
    ) As [ReleasedComponentDetails](topic6336.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [GroupReleasedComponents](topic3238.md)
    Dim componentId As Guid
    Dim throwIfMissing As Boolean
    Dim value As [ReleasedComponentDetails](topic6336.md)
     
    value = instance.GetComponentDetailsById(componentId, throwIfMissing)  
  
C#|   
---|---  
      
    
    public [ReleasedComponentDetails](topic6336.md) GetComponentDetailsById( 
       Guid _componentId_ ,
       bool _throwIfMissing_
    )  
  
#### Parameters

 _componentId_
    The unique identifier of the component.
_throwIfMissing_
    Throws an exception if a component with the specified identiifer cannot be found, if false, a null reference is returned if the component isn't found.

#### Return Value

The component's details.

# Exceptions

Exception| Description  
---|---  
[ItemNotFoundException](topic3571.md)| No component could be found with the specified path.  
  
# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[GroupReleasedComponents Class](topic3238.md)   
[GroupReleasedComponents Members](topic3239.md)


