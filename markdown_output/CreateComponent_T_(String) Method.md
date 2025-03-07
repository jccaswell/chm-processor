_T_
    The type of component to create.

Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
CreateComponent<T>(String) Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [GroupCapturedComponents Class](topic3022.md) > [CreateComponent Method](topic3031.md) : CreateComponent<T>(String) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_path_
    The path to the file represented by the component.

Glossary Item Box

Creates and returns a new component of the specified type without registering it with the group. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Overloads Function CreateComponent(Of T As [CapturedComponent](topic6147.md))( _
       ByVal _path_ As String _
    ) As T  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [GroupCapturedComponents](topic3022.md)
    Dim path As String
    Dim value As T
     
    value = instance.CreateComponent(Of T)(path)  
  
C#|   
---|---  
      
    
    public T CreateComponent<T>( 
       string _path_
    )
    where T: [CapturedComponent](topic6147.md)  
  
#### Parameters

 _path_
    The path to the file represented by the component.

#### Type Parameters

_T_
    The type of component to create.

#### Return Value

A new component of the specified type.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[GroupCapturedComponents Class](topic3022.md)   
[GroupCapturedComponents Members](topic3023.md)   
[Overload List](topic3031.md)


