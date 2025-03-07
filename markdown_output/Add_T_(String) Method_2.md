_T_
    The type of the condition to create. This type must inherit from [ComponentTaskReleaseCondition](topic6647.md).

Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
Add<T>(String) Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Components.Tasks Namespace](topic6391.md) > [ComponentTaskReleaseConditions Class](topic6682.md) > [Add Method](topic6688.md) : Add<T>(String) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_title_
    The title of the condition to create.

Glossary Item Box

Creates a new [ComponentTaskReleaseCondition](topic6647.md) of type T and adds it to the collection. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Overloads Function Add(Of T As [ComponentTaskReleaseCondition](topic6647.md))( _
       ByVal _title_ As String _
    ) As T  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ComponentTaskReleaseConditions](topic6682.md)
    Dim title As String
    Dim value As T
     
    value = instance.Add(Of T)(title)  
  
C#|   
---|---  
      
    
    public T Add<T>( 
       string _title_
    )
    where T: [ComponentTaskReleaseCondition](topic6647.md)  
  
#### Parameters

 _title_
    The title of the condition to create.

#### Type Parameters

_T_
    The type of the condition to create. This type must inherit from [ComponentTaskReleaseCondition](topic6647.md).

#### Return Value

The newly created condition.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ComponentTaskReleaseConditions Class](topic6682.md)   
[ComponentTaskReleaseConditions Members](topic6683.md)   
[Overload List](topic6688.md)


