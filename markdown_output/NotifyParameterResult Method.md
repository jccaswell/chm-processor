Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
NotifyParameterResult Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Components Namespace](topic6089.md) > [IReleaseParameterTracker Interface](topic6113.md) : NotifyParameterResult Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_parameterTypeName_
    The invariant name of the parameter's type.

_parameterTypeDisplayName_
    The display name of the parameter's type.

_parameterName_
    The display name of the parameter.

_parameterRule_
    The rule which was used to calculate the parameter's result.

_parameterResult_
    The result of calculating the parameter's rule.

Glossary Item Box

Called when a parameter result is finalized. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Sub NotifyParameterResult( _
       ByVal _parameterTypeName_ As String, _
       ByVal _parameterTypeDisplayName_ As String, _
       ByVal _parameterName_ As String, _
       ByVal _parameterRule_ As String, _
       ByVal _parameterResult_ As String _
    )   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [IReleaseParameterTracker](topic6113.md)
    Dim parameterTypeName As String
    Dim parameterTypeDisplayName As String
    Dim parameterName As String
    Dim parameterRule As String
    Dim parameterResult As String
     
    instance.NotifyParameterResult(parameterTypeName, parameterTypeDisplayName, parameterName, parameterRule, parameterResult)  
  
C#|   
---|---  
      
    
    void NotifyParameterResult( 
       string _parameterTypeName_ ,
       string _parameterTypeDisplayName_ ,
       string _parameterName_ ,
       string _parameterRule_ ,
       string _parameterResult_
    )  
  
#### Parameters

 _parameterTypeName_
    The invariant name of the parameter's type.
_parameterTypeDisplayName_
    The display name of the parameter's type.
_parameterName_
    The display name of the parameter.
_parameterRule_
    The rule which was used to calculate the parameter's result.
_parameterResult_
    The result of calculating the parameter's rule.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[IReleaseParameterTracker Interface](topic6113.md)   
[IReleaseParameterTracker Members](topic6114.md)


