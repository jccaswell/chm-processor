_T_
    The type of the task to add.

Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
CreateTask<T>(String,Boolean) Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Specification Namespace](topic10764.md) > [TaskSequence Class](topic11713.md) > [CreateTask Method](topic11720.md) : CreateTask<T>(String,Boolean) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_title_
    The title of the task

_createConnection_
    True to create a connection between this task and the previously added task. (Or Start if no other task has been added).

Glossary Item Box

Creates and adds a new task to the task sequence. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Overloads Function CreateTask(Of T As [Task](topic11629.md))( _
       ByVal _title_ As String, _
       ByVal _createConnection_ As Boolean _
    ) As T  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [TaskSequence](topic11713.md)
    Dim title As String
    Dim createConnection As Boolean
    Dim value As T
     
    value = instance.CreateTask(Of T)(title, createConnection)  
  
C#|   
---|---  
      
    
    public T CreateTask<T>( 
       string _title_ ,
       bool _createConnection_
    )
    where T: [Task](topic11629.md)  
  
#### Parameters

 _title_
    The title of the task
 _createConnection_
    True to create a connection between this task and the previously added task. (Or Start if no other task has been added).

#### Type Parameters

_T_
    The type of the task to add.

#### Return Value

The newly created task.

# Exceptions

Exception| Description  
---|---  
System.ArgumentOutOfRangeException| The type specified in for the type parameter T isn't defined in a extension library.  
  
# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[TaskSequence Class](topic11713.md)   
[TaskSequence Members](topic11714.md)   
[Overload List](topic11720.md)


