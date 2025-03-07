Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
GetRule Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [ProjectCalculationTableColumn Class](topic3946.md) : GetRule Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_rowIndex_
    The index of the row to get, where 0 is the first data row.

_create_
    Whether or not to create the cell, if it doesn't exist.

Glossary Item Box

Gets an explicit rule from this column for the specified row. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function GetRule( _
       ByVal _rowIndex_ As Integer, _
       Optional ByVal _create_ As Boolean _
    ) As [ProjectCalculationTableRule](topic3986.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ProjectCalculationTableColumn](topic3946.md)
    Dim rowIndex As Integer
    Dim create As Boolean
    Dim value As [ProjectCalculationTableRule](topic3986.md)
     
    value = instance.GetRule(rowIndex, create)  
  
C#|   
---|---  
      
    
    public [ProjectCalculationTableRule](topic3986.md) GetRule( 
       int _rowIndex_ ,
       bool _create_
    )  
  
#### Parameters

 _rowIndex_
    The index of the row to get, where 0 is the first data row.
_create_
    Whether or not to create the cell, if it doesn't exist.

#### Return Value

The matching cell item if it exists, or null when create is false.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ProjectCalculationTableColumn Class](topic3946.md)   
[ProjectCalculationTableColumn Members](topic3947.md)


