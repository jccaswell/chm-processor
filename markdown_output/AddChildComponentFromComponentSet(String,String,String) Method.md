Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
AddChildComponentFromComponentSet(String,String,String) Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Components Namespace](topic6089.md) > [ReleaseComponentController Class](topic6252.md) > [AddChildComponentFromComponentSet Method](topic6258.md) : AddChildComponentFromComponentSet(String,String,String) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_childMasterPath_
    The path to the child component to replace.

_childMasterAddress_
    The optional address which further qualifies the child component to replace.

_componentSetName_
    The name of the component set to replace the child with.

Glossary Item Box

Adds the named component set as a child of the component being released. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Overloads Function AddChildComponentFromComponentSet( _
       ByVal _childMasterPath_ As String, _
       ByVal _childMasterAddress_ As String, _
       ByVal _componentSetName_ As String _
    ) As Boolean  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ReleaseComponentController](topic6252.md)
    Dim childMasterPath As String
    Dim childMasterAddress As String
    Dim componentSetName As String
    Dim value As Boolean
     
    value = instance.AddChildComponentFromComponentSet(childMasterPath, childMasterAddress, componentSetName)  
  
C#|   
---|---  
      
    
    public bool AddChildComponentFromComponentSet( 
       string _childMasterPath_ ,
       string _childMasterAddress_ ,
       string _componentSetName_
    )  
  
#### Parameters

 _childMasterPath_
    The path to the child component to replace.
_childMasterAddress_
    The optional address which further qualifies the child component to replace.
_componentSetName_
    The name of the component set to replace the child with.

#### Return Value

True if the component set was found and added, otherwise false.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ReleaseComponentController Class](topic6252.md)   
[ReleaseComponentController Members](topic6253.md)   
[Overload List](topic6258.md)


