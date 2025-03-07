Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
RegisterContextualCommand(String,StateFilter,ICommandContextHelper,Boolean) Method   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications Namespace](topic16.md) > [ICommandManager Interface](topic143.md) > [RegisterContextualCommand Method](topic153.md) : RegisterContextualCommand(String,StateFilter,ICommandContextHelper,Boolean) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_commandName_
    The culture invariant name of the command.

_stateFilter_
    A filter which describes in which application states the command is available.

_contextHelper_
    A helper object which provides information and validation for commands which support context.

_enabled_
    True if the command is enabled by default, otherwise false.

Glossary Item Box

Registers the given contextual command with the command manager. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Overloads Function RegisterContextualCommand( _
       ByVal _commandName_ As String, _
       ByVal _stateFilter_ As [StateFilter](topic1077.md), _
       ByVal _contextHelper_ As [ICommandContextHelper](topic135.md), _
       ByVal _enabled_ As Boolean _
    ) As [ICommand](topic77.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ICommandManager](topic143.md)
    Dim commandName As String
    Dim stateFilter As [StateFilter](topic1077.md)
    Dim contextHelper As [ICommandContextHelper](topic135.md)
    Dim enabled As Boolean
    Dim value As [ICommand](topic77.md)
     
    value = instance.RegisterContextualCommand(commandName, stateFilter, contextHelper, enabled)  
  
C#|   
---|---  
      
    
    [ICommand](topic77.md) RegisterContextualCommand( 
       string _commandName_ ,
       [StateFilter](topic1077.md) _stateFilter_ ,
       [ICommandContextHelper](topic135.md) _contextHelper_ ,
       bool _enabled_
    )  
  
#### Parameters

 _commandName_
    The culture invariant name of the command.
_stateFilter_
    A filter which describes in which application states the command is available.
_contextHelper_
    A helper object which provides information and validation for commands which support context.
_enabled_
    True if the command is enabled by default, otherwise false.

#### Return Value

An implementation of the [ICommand](topic77.md) interface representing the newly registered command.

# Remarks

Commands can be classified as context-aware, or basic commands. A context-aware command is one which changes its behavior depending on the contextual data passed to its invoke method, it may also provide a custom title and description based on the context to which it is applied.

One example of a context-aware command would be the open group command, without any context, this command will show the open group dialog, however, context data could also be specified identifying the specific group to open.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ICommandManager Interface](topic143.md)   
[ICommandManager Members](topic144.md)   
[Overload List](topic153.md)


