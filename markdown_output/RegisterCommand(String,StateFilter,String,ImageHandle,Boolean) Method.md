Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
RegisterCommand(String,StateFilter,String,ImageHandle,Boolean) Method   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications Namespace](topic16.md) > [ICommandManager Interface](topic143.md) > [RegisterCommand Method](topic150.md) : RegisterCommand(String,StateFilter,String,ImageHandle,Boolean) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_commandName_
    The culture invariant name of the command.

_stateFilter_
    A filter which describes in which application states the command is available.

_commandTitle_
    The localized title of the command.

_commandImage_
    An image handle which provides a UI representation of the command.

_enabled_
    True if the command is enabled by default, otherwise false.

Glossary Item Box

Registers the given command with the command manager. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Overloads Function RegisterCommand( _
       ByVal _commandName_ As String, _
       ByVal _stateFilter_ As [StateFilter](topic1077.md), _
       ByVal _commandTitle_ As String, _
       ByVal _commandImage_ As [ImageHandle](topic854.md), _
       ByVal _enabled_ As Boolean _
    ) As [ICommand](topic77.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ICommandManager](topic143.md)
    Dim commandName As String
    Dim stateFilter As [StateFilter](topic1077.md)
    Dim commandTitle As String
    Dim commandImage As [ImageHandle](topic854.md)
    Dim enabled As Boolean
    Dim value As [ICommand](topic77.md)
     
    value = instance.RegisterCommand(commandName, stateFilter, commandTitle, commandImage, enabled)  
  
C#|   
---|---  
      
    
    [ICommand](topic77.md) RegisterCommand( 
       string _commandName_ ,
       [StateFilter](topic1077.md) _stateFilter_ ,
       string _commandTitle_ ,
       [ImageHandle](topic854.md) _commandImage_ ,
       bool _enabled_
    )  
  
#### Parameters

 _commandName_
    The culture invariant name of the command.
_stateFilter_
    A filter which describes in which application states the command is available.
_commandTitle_
    The localized title of the command.
_commandImage_
    An image handle which provides a UI representation of the command.
_enabled_
    True if the command is enabled by default, otherwise false.

#### Return Value

An implementation of the [ICommand](topic77.md) interface representing the newly registered command.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ICommandManager Interface](topic143.md)   
[ICommandManager Members](topic144.md)   
[Overload List](topic150.md)


