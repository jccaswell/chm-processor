Remove(CapturedFeatureParameter) Method   
  
[DriveWorks.SolidWorks Assembly](topic13342.md) > [DriveWorks.SolidWorks.Components Namespace](topic13925.md) > [CapturedFeatureParameterCollection Class](topic14225.md) > [Remove Method](topic14234.md) : Remove(CapturedFeatureParameter) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_parameter_
    The parameter to remove from the collection.

Glossary Item Box

Removes the given parameter from the collection. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Overloads Function Remove( _
       ByVal _parameter_ As [CapturedFeatureParameter](topic14218.md) _
    ) As Boolean  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [CapturedFeatureParameterCollection](topic14225.md)
    Dim parameter As [CapturedFeatureParameter](topic14218.md)
    Dim value As Boolean
     
    value = instance.Remove(parameter)  
  
C#|   
---|---  
      
    
    public bool Remove( 
       [CapturedFeatureParameter](topic14218.md) _parameter_
    )  
  
#### Parameters

 _parameter_
    The parameter to remove from the collection.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[CapturedFeatureParameterCollection Class](topic14225.md)   
[CapturedFeatureParameterCollection Members](topic14226.md)   
[Overload List](topic14234.md)


