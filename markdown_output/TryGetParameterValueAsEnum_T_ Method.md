TryGetParameterValueAsEnum<T> Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [ReleasedComponentTask Class](topic5061.md) : TryGetParameterValueAsEnum<T> Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_name_
    The name of the parameter whose calculated value to retrieve.

_value_
    The calculated value of the parameter if the parameter was found.

Glossary Item Box

Attempts to retrieve the value of the given parameter as an Enum. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function TryGetParameterValueAsEnum(Of T As {New, Struct})( _
       ByVal _name_ As String, _
       ByRef _value_ As T _
    ) As Boolean  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ReleasedComponentTask](topic5061.md)
    Dim name As String
    Dim value As T
    Dim value As Boolean
     
    value = instance.TryGetParameterValueAsEnum(Of T)(name, value)  
  
C#|   
---|---  
      
    
    public bool TryGetParameterValueAsEnum<T>( 
       string _name_ ,
       ref T _value_
    )
    where T: new(), struct  
  
#### Parameters

 _name_
    The name of the parameter whose calculated value to retrieve.
_value_
    The calculated value of the parameter if the parameter was found.

#### Type Parameters

_T_
    The type to convert the released parameter value to.

#### Return Value

True if the parameter was found and its value could successfully be converted to an Enum.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ReleasedComponentTask Class](topic5061.md)   
[ReleasedComponentTask Members](topic5062.md)


