Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
Item Property   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [ProjectComponentTasks Class](topic4163.md) : Item Property  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_key_
    The unique identifier of the collection to retrieve.

Glossary Item Box

Gets the collection with the given key. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public ReadOnly Default Property Item( _
       ByVal _key_ As String _
    ) As [ComponentTaskAccessor](topic6429.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ProjectComponentTasks](topic4163.md)
    Dim key As String
    Dim value As [ComponentTaskAccessor](topic6429.md)
     
    value = instance.Item(key)  
  
C#|   
---|---  
      
    
    public [ComponentTaskAccessor](topic6429.md) this[ 
       string _key_
    ]; {get;}  
  
#### Parameters

 _key_
    The unique identifier of the collection to retrieve.

#### Property Value

The accessor that provides access to the collection associated with the specified key, or a null reference (Nothing in VB) if the accessor does not exist.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ProjectComponentTasks Class](topic4163.md)   
[ProjectComponentTasks Members](topic4164.md)


