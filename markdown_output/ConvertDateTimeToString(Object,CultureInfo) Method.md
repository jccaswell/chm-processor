Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
ConvertDateTimeToString(Object,CultureInfo) Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Forms.DataModel Namespace](topic9371.md) > [StoreConverter Class](topic9528.md) > [ConvertDateTimeToString Method](topic9544.md) : ConvertDateTimeToString(Object,CultureInfo) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_value_
    The source value.

_culture_
    An instance of the System.Globalization.CultureInfo defining how culture-specific conversions should be performed.

Glossary Item Box

Converts a date/time to a string. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Overloads Shared Function ConvertDateTimeToString( _
       ByVal _value_ As Object, _
       ByVal _culture_ As CultureInfo _
    ) As Object  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim value As Object
    Dim culture As CultureInfo
    Dim value As Object
     
    value = [StoreConverter](topic9528.md).ConvertDateTimeToString(value, culture)  
  
C#|   
---|---  
      
    
    public static object ConvertDateTimeToString( 
       object _value_ ,
       CultureInfo _culture_
    )  
  
#### Parameters

 _value_
    The source value.
_culture_
    An instance of the System.Globalization.CultureInfo defining how culture-specific conversions should be performed.

#### Return Value

A date/time.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[StoreConverter Class](topic9528.md)   
[StoreConverter Members](topic9529.md)   
[Overload List](topic9544.md)


