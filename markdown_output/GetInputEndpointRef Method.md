Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
GetInputEndpointRef Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Transactions Namespace](topic12835.md) > [ExecutableNodeRef Class](topic12864.md) : GetInputEndpointRef Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_name_
    The name of the input endpoint.

_isNavigation_
    True if the input endpoint is a navigation endpoint.

Glossary Item Box

Get a reference to one of the node's input endpoints. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function GetInputEndpointRef( _
       ByVal _name_ As String, _
       ByVal _isNavigation_ As Boolean _
    ) As [InputEndpointRef](topic12893.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ExecutableNodeRef](topic12864.md)
    Dim name As String
    Dim isNavigation As Boolean
    Dim value As [InputEndpointRef](topic12893.md)
     
    value = instance.GetInputEndpointRef(name, isNavigation)  
  
C#|   
---|---  
      
    
    public [InputEndpointRef](topic12893.md) GetInputEndpointRef( 
       string _name_ ,
       bool _isNavigation_
    )  
  
#### Parameters

 _name_
    The name of the input endpoint.
_isNavigation_
    True if the input endpoint is a navigation endpoint.

#### Return Value

A reference to an input on this node with the desired name.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ExecutableNodeRef Class](topic12864.md)   
[ExecutableNodeRef Members](topic12865.md)


