Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
CreateFunction Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Localization Namespace](topic10015.md) > [RuleLocalizationHelper Class](topic10018.md) : CreateFunction Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_functionName_
    The English function name which will be localized.

_arguments_
    The arguments to be passed to the function.

Glossary Item Box

Creates a localized function call. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function CreateFunction( _
       ByVal _functionName_ As String, _
       ByVal ParamArray _arguments_() As String _
    ) As String  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [RuleLocalizationHelper](topic10018.md)
    Dim functionName As String
    Dim arguments() As String
    Dim value As String
     
    value = instance.CreateFunction(functionName, arguments)  
  
C#|   
---|---  
      
    
    public string CreateFunction( 
       string _functionName_ ,
       params string[] _arguments_
    )  
  
#### Parameters

 _functionName_
    The English function name which will be localized.
_arguments_
    The arguments to be passed to the function.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[RuleLocalizationHelper Class](topic10018.md)   
[RuleLocalizationHelper Members](topic10019.md)


