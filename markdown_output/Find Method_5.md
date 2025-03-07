Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
Find Method   
  
[DriveWorks.SolidWorks Assembly](topic13342.md) > [DriveWorks.SolidWorks.Components Namespace](topic13925.md) > [CapturedFeatureParameterCollection Class](topic14225.md) : Find Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_address_
    The address of the parameter to look for.

_throwIfMissing_
    True to throw an exception if a parameter with the given address can't be found, otherwise, a null reference is returned.

Glossary Item Box

Looks for an additional feature parameter with the given address. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function Find( _
       ByVal _address_ As String, _
       ByVal _throwIfMissing_ As Boolean _
    ) As [CapturedFeatureParameter](topic14218.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [CapturedFeatureParameterCollection](topic14225.md)
    Dim address As String
    Dim throwIfMissing As Boolean
    Dim value As [CapturedFeatureParameter](topic14218.md)
     
    value = instance.Find(address, throwIfMissing)  
  
C#|   
---|---  
      
    
    public [CapturedFeatureParameter](topic14218.md) Find( 
       string _address_ ,
       bool _throwIfMissing_
    )  
  
#### Parameters

 _address_
    The address of the parameter to look for.
_throwIfMissing_
    True to throw an exception if a parameter with the given address can't be found, otherwise, a null reference is returned.

#### Return Value

A parameter with the specified parameter.

# Exceptions

Exception| Description  
---|---  
[DriveWorks.ItemNotFoundException](topic3571.md)| A parameter with the given address couldn't be found.  
  
# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[CapturedFeatureParameterCollection Class](topic14225.md)   
[CapturedFeatureParameterCollection Members](topic14226.md)


