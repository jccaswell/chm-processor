Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
AddInput Method   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications.Autopilot.Extensibility Namespace](topic1633.md) > [ISpecificationRequest Interface](topic1778.md) : AddInput Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_inputName_
    The name of the constant or form control to change.

_inputValue_
    The value to drive.

Glossary Item Box

Adds an input to be changed in the specification. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Sub AddInput( _
       ByVal _inputName_ As String, _
       ByVal _inputValue_ As String _
    )   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ISpecificationRequest](topic1778.md)
    Dim inputName As String
    Dim inputValue As String
     
    instance.AddInput(inputName, inputValue)  
  
C#|   
---|---  
      
    
    void AddInput( 
       string _inputName_ ,
       string _inputValue_
    )  
  
#### Parameters

 _inputName_
    The name of the constant or form control to change.
_inputValue_
    The value to drive.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ISpecificationRequest Interface](topic1778.md)   
[ISpecificationRequest Members](topic1779.md)


