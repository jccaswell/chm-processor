Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
InvokeTransition(String) Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Specification Namespace](topic10764.md) > [SpecificationContext Class](topic11149.md) > [InvokeTransition Method](topic11173.md) : InvokeTransition(String) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_transitionName_
    The name of the transition to invoke.

Glossary Item Box

Invokes the specified transition. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Overloads Function InvokeTransition( _
       ByVal _transitionName_ As String _
    ) As Boolean  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [SpecificationContext](topic11149.md)
    Dim transitionName As String
    Dim value As Boolean
     
    value = instance.InvokeTransition(transitionName)  
  
C#|   
---|---  
      
    
    public bool InvokeTransition( 
       string _transitionName_
    )  
  
#### Parameters

 _transitionName_
    The name of the transition to invoke.

#### Return Value

True if the transition was successfully invoked, false if one or more conditions caused the transition to be aborted.

# Exceptions

Exception| Description  
---|---  
[DriveWorks.ItemNotFoundException](topic3571.md)| The specified transition does not exist for the current state.  
System.UnauthorizedAccessException| Thrown if the current user does not have permission to invoke the transition.  
[SpecificationExistsException](topic11376.md)| The specification name is already registered.  
[SpecificationNameInvalidException](topic11488.md)| The specification name contains invalid characters, starts/ends with whitespace, or is too long.  
System.IO.PathTooLongException| One or more paths are too long to complete the specification, most likely the calculated project or specification file name.  
System.InvalidOperationException| The transition can't be invoked because an operation or transition is already being processed, or because the transition takes one running state to another running state.  
[TaskExecutionException](topic11683.md)| The transition can't be invoked because a task threw an unhandled exception.  
  
# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[SpecificationContext Class](topic11149.md)   
[SpecificationContext Members](topic11150.md)   
[Overload List](topic11173.md)


