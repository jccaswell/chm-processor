Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
PushStep Method   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications Namespace](topic16.md) > [WizardBase Class](topic1200.md) : PushStep Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_stepControl_
    The step to push on to the stack.

_isCancelEnabled_
    True if the cancel button should be enabled when the step is activated.

_isPreviousEnabled_
    True if the previous button should be enabled when the step is activated.

_isNextEnabled_
    True if the next button should be enabled when the step is activated.

_isFinishEnabled_
    True if the finish button should be enabled when the step is activated.

Glossary Item Box

Manual pushes a step on to the list of previous steps. May be useful if GetInitialStep returns a step other than the zeroeth. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Protected Sub PushStep( _
       ByVal _stepControl_ As Control, _
       ByVal _isCancelEnabled_ As Boolean, _
       ByVal _isPreviousEnabled_ As Boolean, _
       ByVal _isNextEnabled_ As Boolean, _
       ByVal _isFinishEnabled_ As Boolean _
    )   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [WizardBase](topic1200.md)
    Dim stepControl As Control
    Dim isCancelEnabled As Boolean
    Dim isPreviousEnabled As Boolean
    Dim isNextEnabled As Boolean
    Dim isFinishEnabled As Boolean
     
    instance.PushStep(stepControl, isCancelEnabled, isPreviousEnabled, isNextEnabled, isFinishEnabled)  
  
C#|   
---|---  
      
    
    protected void PushStep( 
       Control _stepControl_ ,
       bool _isCancelEnabled_ ,
       bool _isPreviousEnabled_ ,
       bool _isNextEnabled_ ,
       bool _isFinishEnabled_
    )  
  
#### Parameters

 _stepControl_
    The step to push on to the stack.
_isCancelEnabled_
    True if the cancel button should be enabled when the step is activated.
_isPreviousEnabled_
    True if the previous button should be enabled when the step is activated.
_isNextEnabled_
    True if the next button should be enabled when the step is activated.
_isFinishEnabled_
    True if the finish button should be enabled when the step is activated.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[WizardBase Class](topic1200.md)   
[WizardBase Members](topic1201.md)


