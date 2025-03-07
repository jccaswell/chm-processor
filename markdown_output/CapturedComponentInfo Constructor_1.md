Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
CapturedComponentInfo Constructor   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Components Namespace](topic6089.md) > [CapturedComponentInfo Class](topic6154.md) : CapturedComponentInfo Constructor  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_id_
    The unique identifier assigned to the group.

_type_
    The component's type.

_path_
    The path to the component.

_references_
    An array of identifiers of components referenced as children of the component.

_isDeleted_
    A value which indicates whether the component is deleted.

Glossary Item Box

Initializes a new instance of the [CapturedComponentInfo](topic6154.md) type. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function New( _
       ByVal _id_ As Guid, _
       ByVal _type_ As String, _
       ByVal _path_ As String, _
       ByVal _references_() As Guid, _
       ByVal _isDeleted_ As Boolean _
    )  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim id As Guid
    Dim type As String
    Dim path As String
    Dim references() As Guid
    Dim isDeleted As Boolean
     
    Dim instance As New [CapturedComponentInfo](topic6154.md)(id, type, path, references, isDeleted)  
  
C#|   
---|---  
      
    
    public CapturedComponentInfo( 
       Guid _id_ ,
       string _type_ ,
       string _path_ ,
       Guid[] _references_ ,
       bool _isDeleted_
    )  
  
#### Parameters

 _id_
    The unique identifier assigned to the group.
_type_
    The component's type.
_path_
    The path to the component.
_references_
    An array of identifiers of components referenced as children of the component.
_isDeleted_
    A value which indicates whether the component is deleted.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[CapturedComponentInfo Class](topic6154.md)   
[CapturedComponentInfo Members](topic6155.md)


