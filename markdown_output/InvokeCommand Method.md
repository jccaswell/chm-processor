Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
InvokeCommand Method   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications Namespace](topic16.md) > [ICommandManager Interface](topic143.md) : InvokeCommand Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_commandName_
    The name of the command to execute.

_commandContext_
    The context to be passed to the command, or a null reference (Nothing in Visual Basic).

Glossary Item Box

Invokes the specified command using the given arguments. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Function InvokeCommand( _
       ByVal _commandName_ As String, _
       ByVal _commandContext_ As Object _
    ) As Boolean  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ICommandManager](topic143.md)
    Dim commandName As String
    Dim commandContext As Object
    Dim value As Boolean
     
    value = instance.InvokeCommand(commandName, commandContext)  
  
C#|   
---|---  
      
    
    bool InvokeCommand( 
       string _commandName_ ,
       object _commandContext_
    )  
  
#### Parameters

 _commandName_
    The name of the command to execute.
_commandContext_
    The context to be passed to the command, or a null reference (Nothing in Visual Basic).

#### Return Value

True if the command was found and invoked, false if the command was not registered.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ICommandManager Interface](topic143.md)   
[ICommandManager Members](topic144.md)


