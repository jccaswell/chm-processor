Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
GetTaskRef Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Transactions Namespace](topic12835.md) > [TaskSequenceRef Class](topic13159.md) : GetTaskRef Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_taskIndex_
    The index of the task in the sequence.

Glossary Item Box

Gets a reference to the specified task. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function GetTaskRef( _
       ByVal _taskIndex_ As Integer _
    ) As [TaskRef](topic13149.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [TaskSequenceRef](topic13159.md)
    Dim taskIndex As Integer
    Dim value As [TaskRef](topic13149.md)
     
    value = instance.GetTaskRef(taskIndex)  
  
C#|   
---|---  
      
    
    public [TaskRef](topic13149.md) GetTaskRef( 
       int _taskIndex_
    )  
  
#### Parameters

 _taskIndex_
    The index of the task in the sequence.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[TaskSequenceRef Class](topic13159.md)   
[TaskSequenceRef Members](topic13160.md)


