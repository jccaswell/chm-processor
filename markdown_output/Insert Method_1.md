Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
Insert Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [ProjectComponentSets Class](topic4143.md) : Insert Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_name_
    The name to give to the component set, if a null reference is specified, the file name of the base component (with an optional numeric suffix if required) will be used.

_capturedComponentId_
    The identifier of the captured component on which to base the component set.

_index_
    The index at which to insert the new component set.

Glossary Item Box

Inserts a new project component set at the specified index. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function Insert( _
       ByVal _name_ As String, _
       ByVal _capturedComponentId_ As Guid, _
       ByVal _index_ As Integer _
    ) As [ProjectComponentSet](topic4106.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ProjectComponentSets](topic4143.md)
    Dim name As String
    Dim capturedComponentId As Guid
    Dim index As Integer
    Dim value As [ProjectComponentSet](topic4106.md)
     
    value = instance.Insert(name, capturedComponentId, index)  
  
C#|   
---|---  
      
    
    public [ProjectComponentSet](topic4106.md) Insert( 
       string _name_ ,
       Guid _capturedComponentId_ ,
       int _index_
    )  
  
#### Parameters

 _name_
    The name to give to the component set, if a null reference is specified, the file name of the base component (with an optional numeric suffix if required) will be used.
_capturedComponentId_
    The identifier of the captured component on which to base the component set.
_index_
    The index at which to insert the new component set.

#### Return Value

The new project component set.

# Remarks

ArgumentOutOfRangeException will be thrown if the supplied index is less than 0 or greater than the collection's size.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ProjectComponentSets Class](topic4143.md)   
[ProjectComponentSets Members](topic4144.md)


