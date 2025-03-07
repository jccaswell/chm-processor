Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
GenericRuleResultToDisplayString Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [ProjectUtility Class](topic4899.md) : GenericRuleResultToDisplayString Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_value_
    The value to convert.

_ci_
    The culture to use when converting.

Glossary Item Box

Converts the result of a rule calcuation to a human readable string. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Shared Function GenericRuleResultToDisplayString( _
       ByVal _value_ As Object, _
       ByVal _ci_ As CultureInfo _
    ) As String  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim value As Object
    Dim ci As CultureInfo
    Dim value As String
     
    value = [ProjectUtility](topic4899.md).GenericRuleResultToDisplayString(value, ci)  
  
C#|   
---|---  
      
    
    public static string GenericRuleResultToDisplayString( 
       object _value_ ,
       CultureInfo _ci_
    )  
  
#### Parameters

 _value_
    The value to convert.
_ci_
    The culture to use when converting.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ProjectUtility Class](topic4899.md)   
[ProjectUtility Members](topic4900.md)


