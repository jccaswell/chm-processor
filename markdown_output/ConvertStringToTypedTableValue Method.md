Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
ConvertStringToTypedTableValue Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Forms.DataModel Namespace](topic9371.md) > [StoreConverter Class](topic9528.md) : ConvertStringToTypedTableValue Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_value_
    The source value.

Glossary Item Box

Converts the specified string to a table. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Shared Function ConvertStringToTypedTableValue( _
       ByVal _value_ As Object _
    ) As [ITableValue](topic2331.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim value As Object
    Dim value As [ITableValue](topic2331.md)
     
    value = [StoreConverter](topic9528.md).ConvertStringToTypedTableValue(value)  
  
C#|   
---|---  
      
    
    public static [ITableValue](topic2331.md) ConvertStringToTypedTableValue( 
       object _value_
    )  
  
#### Parameters

 _value_
    The source value.

#### Return Value

A table.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[StoreConverter Class](topic9528.md)   
[StoreConverter Members](topic9529.md)


