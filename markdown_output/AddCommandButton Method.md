Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
AddCommandButton Method   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications Namespace](topic16.md) > [ICommandBarGroup Interface](topic99.md) : AddCommandButton Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_commandName_
    The name of the command to invoke when the command button is clicked.

_commandContext_
    The context to pass to the command when the command button is clicked.

_displayHint_
    The layout hint to be applied by the command bar manager when laying out the command button.

_unavailableBehavior_
    The behavior of the command button element when the command is unavailable.

Glossary Item Box

Adds a new command button to the group. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Function AddCommandButton( _
       ByVal _commandName_ As String, _
       ByVal _commandContext_ As Object, _
       ByVal _displayHint_ As [CommandBarDisplayHint](topic657.md), _
       ByVal _unavailableBehavior_ As [CommandUnavailableBehavior](topic659.md) _
    ) As [ICommandButton](topic115.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ICommandBarGroup](topic99.md)
    Dim commandName As String
    Dim commandContext As Object
    Dim displayHint As [CommandBarDisplayHint](topic657.md)
    Dim unavailableBehavior As [CommandUnavailableBehavior](topic659.md)
    Dim value As [ICommandButton](topic115.md)
     
    value = instance.AddCommandButton(commandName, commandContext, displayHint, unavailableBehavior)  
  
C#|   
---|---  
      
    
    [ICommandButton](topic115.md) AddCommandButton( 
       string _commandName_ ,
       object _commandContext_ ,
       [CommandBarDisplayHint](topic657.md) _displayHint_ ,
       [CommandUnavailableBehavior](topic659.md) _unavailableBehavior_
    )  
  
#### Parameters

 _commandName_
    The name of the command to invoke when the command button is clicked.
_commandContext_
    The context to pass to the command when the command button is clicked.
_displayHint_
    The layout hint to be applied by the command bar manager when laying out the command button.
_unavailableBehavior_
    The behavior of the command button element when the command is unavailable.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ICommandBarGroup Interface](topic99.md)   
[ICommandBarGroup Members](topic100.md)


