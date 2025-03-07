TableCellValueToDisplayString Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [ProjectUtility Class](topic4899.md) : TableCellValueToDisplayString Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_value_
    The table cell's value to convert.

_culture_
    The culture info to use, if null is specified the current UI culture is used.

Glossary Item Box

Converts the specified table cell's value to a string suitable for display. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    <EditorBrowsableAttribute(EditorBrowsableState.Advanced)>
    Public Function TableCellValueToDisplayString( _
       ByVal _value_ As Object, _
       ByVal _culture_ As CultureInfo _
    ) As String  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ProjectUtility](topic4899.md)
    Dim value As Object
    Dim culture As CultureInfo
    Dim value As String
     
    value = instance.TableCellValueToDisplayString(value, culture)  
  
C#|   
---|---  
      
    
    [EditorBrowsableAttribute(EditorBrowsableState.Advanced)]
    public string TableCellValueToDisplayString( 
       object _value_ ,
       CultureInfo _culture_
    )  
  
#### Parameters

 _value_
    The table cell's value to convert.
_culture_
    The culture info to use, if null is specified the current UI culture is used.

#### Return Value

The display string for the table cell's value.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ProjectUtility Class](topic4899.md)   
[ProjectUtility Members](topic4900.md)


