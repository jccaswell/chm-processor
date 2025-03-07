Remove(ComponentTask) Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Components.Tasks Namespace](topic6391.md) > [ComponentTaskCollection Class](topic6466.md) : Remove(ComponentTask) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_task_
    The task to remove.

Glossary Item Box

Removes the given task from the collection and deletes it from the project. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function Remove( _
       ByVal _task_ As [ComponentTask](topic6407.md) _
    ) As Boolean  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ComponentTaskCollection](topic6466.md)
    Dim task As [ComponentTask](topic6407.md)
    Dim value As Boolean
     
    value = instance.Remove(task)  
  
C#|   
---|---  
      
    
    public bool Remove( 
       [ComponentTask](topic6407.md) _task_
    )  
  
#### Parameters

 _task_
    The task to remove.

#### Return Value

True if the task was successfully removed.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ComponentTaskCollection Class](topic6466.md)   
[ComponentTaskCollection Members](topic6467.md)


