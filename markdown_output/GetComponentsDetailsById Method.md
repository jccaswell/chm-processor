Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
GetComponentsDetailsById Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [GroupReleasedComponents Class](topic3238.md) : GetComponentsDetailsById Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_componentIds_
    The unique identifiers of the components to retrieve the details of.

Glossary Item Box

Gets the details of all driven components matching the specified component ids. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function GetComponentsDetailsById( _
       ByVal _componentIds_() As Guid _
    ) As [ReleasedComponentDetails()](topic6336.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [GroupReleasedComponents](topic3238.md)
    Dim componentIds() As Guid
    Dim value() As [ReleasedComponentDetails](topic6336.md)
     
    value = instance.GetComponentsDetailsById(componentIds)  
  
C#|   
---|---  
      
    
    public [ReleasedComponentDetails[]](topic6336.md) GetComponentsDetailsById( 
       Guid[] _componentIds_
    )  
  
#### Parameters

 _componentIds_
    The unique identifiers of the components to retrieve the details of.

#### Return Value

An array of driven component details matching the specified component ids.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[GroupReleasedComponents Class](topic3238.md)   
[GroupReleasedComponents Members](topic3239.md)


