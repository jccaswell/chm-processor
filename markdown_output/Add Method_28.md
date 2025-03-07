Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
Add Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [ProjectCalculationTableColumns Class](topic3968.md) : Add Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_displayName_
    The display name of this column (can contain spaces).

_type_
    The type of column to create.

Glossary Item Box

Adds a new column to this collection of columns. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function Add( _
       ByVal _displayName_ As String, _
       ByVal _type_ As [ProjectCalculationTableColumnType](topic2356.md) _
    ) As [ProjectCalculationTableColumn](topic3946.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ProjectCalculationTableColumns](topic3968.md)
    Dim displayName As String
    Dim type As [ProjectCalculationTableColumnType](topic2356.md)
    Dim value As [ProjectCalculationTableColumn](topic3946.md)
     
    value = instance.Add(displayName, type)  
  
C#|   
---|---  
      
    
    public [ProjectCalculationTableColumn](topic3946.md) Add( 
       string _displayName_ ,
       [ProjectCalculationTableColumnType](topic2356.md) _type_
    )  
  
#### Parameters

 _displayName_
    The display name of this column (can contain spaces).
_type_
    The type of column to create.

#### Return Value

The created column.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ProjectCalculationTableColumns Class](topic3968.md)   
[ProjectCalculationTableColumns Members](topic3969.md)


