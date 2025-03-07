Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
Get(String) Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Components.Tasks Namespace](topic6391.md) > [ComponentTaskAccessor Class](topic6429.md) > [Get Method](topic6442.md) : Get(String) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_name_
    The name of the task to get.

Glossary Item Box

Gets the task with the given name in the collection (or a null reference if the task doesn't exist). 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Overloads Function Get( _
       ByVal _name_ As String _
    ) As [ComponentTask](topic6407.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ComponentTaskAccessor](topic6429.md)
    Dim name As String
    Dim value As [ComponentTask](topic6407.md)
     
    value = instance.Get(name)  
  
C#|   
---|---  
      
    
    public [ComponentTask](topic6407.md) Get( 
       string _name_
    )  
  
#### Parameters

 _name_
    The name of the task to get.

#### Return Value

The task with the given name if it's present in the collection, otherwise a null reference.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ComponentTaskAccessor Class](topic6429.md)   
[ComponentTaskAccessor Members](topic6430.md)   
[Overload List](topic6442.md)


