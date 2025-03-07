Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
Add Method   
  
[DriveWorks.SolidWorks Assembly](topic13342.md) > [DriveWorks.SolidWorks.Components Namespace](topic13925.md) > [ReleasedFeatureParameterCollection Class](topic14911.md) : Add Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_address_
    The address of the parameter.

_value_
    The value of the feature parameter.

Glossary Item Box

Adds a new feature parameter to the collection. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function Add( _
       ByVal _address_ As String, _
       ByVal _value_ As String _
    ) As [ReleasedFeatureParameter](topic14903.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ReleasedFeatureParameterCollection](topic14911.md)
    Dim address As String
    Dim value As String
    Dim value As [ReleasedFeatureParameter](topic14903.md)
     
    value = instance.Add(address, value)  
  
C#|   
---|---  
      
    
    public [ReleasedFeatureParameter](topic14903.md) Add( 
       string _address_ ,
       string _value_
    )  
  
#### Parameters

 _address_
    The address of the parameter.
_value_
    The value of the feature parameter.

#### Return Value

The newly created parameter.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ReleasedFeatureParameterCollection Class](topic14911.md)   
[ReleasedFeatureParameterCollection Members](topic14912.md)


