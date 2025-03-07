Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
CreateTask(Type,String) Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Specification Namespace](topic10764.md) > [TaskSequence Class](topic11713.md) > [CreateTask Method](topic11720.md) : CreateTask(Type,String) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_taskType_
    The type of the task to add.

_title_
    The title of the task

Glossary Item Box

Creates and adds a new task to the task sequence. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Overloads Function CreateTask( _
       ByVal _taskType_ As Type, _
       ByVal _title_ As String _
    ) As [Task](topic11629.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [TaskSequence](topic11713.md)
    Dim taskType As Type
    Dim title As String
    Dim value As [Task](topic11629.md)
     
    value = instance.CreateTask(taskType, title)  
  
C#|   
---|---  
      
    
    public [Task](topic11629.md) CreateTask( 
       Type _taskType_ ,
       string _title_
    )  
  
#### Parameters

 _taskType_
    The type of the task to add.
_title_
    The title of the task

#### Return Value

The newly created task.

# Exceptions

Exception| Description  
---|---  
System.ArgumentOutOfRangeException| The type specified in taskType does not inherit from [Task](topic11629.md) or isn't defined in a extension library.  
  
# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[TaskSequence Class](topic11713.md)   
[TaskSequence Members](topic11714.md)   
[Overload List](topic11720.md)


