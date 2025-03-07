Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
GetDelimitedLine Method   
  
[DriveWorks.SolidWorks Assembly](topic13342.md) > [DriveWorks.SolidWorks Namespace](topic13345.md) > [ClipboardSupport Class](topic13507.md) : GetDelimitedLine Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_delimiter_
    The delimiter to use.

_values_
    The values to convert.

Glossary Item Box

Converts the specified array of values into a delimited line of text. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Shared Function GetDelimitedLine( _
       ByVal _delimiter_ As String, _
       ByVal ParamArray _values_() As String _
    ) As String  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim delimiter As String
    Dim values() As String
    Dim value As String
     
    value = [ClipboardSupport](topic13507.md).GetDelimitedLine(delimiter, values)  
  
C#|   
---|---  
      
    
    public static string GetDelimitedLine( 
       string _delimiter_ ,
       params string[] _values_
    )  
  
#### Parameters

 _delimiter_
    The delimiter to use.
_values_
    The values to convert.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ClipboardSupport Class](topic13507.md)   
[ClipboardSupport Members](topic13508.md)


