Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
GetConverter Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Forms.DataModel Namespace](topic9371.md) > [DynamicProperty Class](topic9398.md) : GetConverter Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_clrType_
    The CLR type for which to get a property value converter.

_throwOnError_
    True to throw an System.ArgumentOutOfRangeException if no converter is found, otherwise false.

Glossary Item Box

Gets the property value converter for the given CLR type. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Shared Function GetConverter( _
       ByVal _clrType_ As Type, _
       ByVal _throwOnError_ As Boolean _
    ) As [IPropertyValueConverter](topic9373.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim clrType As Type
    Dim throwOnError As Boolean
    Dim value As [IPropertyValueConverter](topic9373.md)
     
    value = [DynamicProperty](topic9398.md).GetConverter(clrType, throwOnError)  
  
C#|   
---|---  
      
    
    public static [IPropertyValueConverter](topic9373.md) GetConverter( 
       Type _clrType_ ,
       bool _throwOnError_
    )  
  
#### Parameters

 _clrType_
    The CLR type for which to get a property value converter.
_throwOnError_
    True to throw an System.ArgumentOutOfRangeException if no converter is found, otherwise false.

#### Return Value

The property value converter for the given CLR type, or a null reference if none is found and throwOnError is false.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[DynamicProperty Class](topic9398.md)   
[DynamicProperty Members](topic9399.md)


