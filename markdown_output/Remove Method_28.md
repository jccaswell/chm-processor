Remove Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [ProjectCalculationTableColumns Class](topic3968.md) : Remove Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_column_
    The column to remove.

Glossary Item Box

Removes a column the collection of columns. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function Remove( _
       ByVal _column_ As [ProjectCalculationTableColumn](topic3946.md) _
    ) As Boolean  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ProjectCalculationTableColumns](topic3968.md)
    Dim column As [ProjectCalculationTableColumn](topic3946.md)
    Dim value As Boolean
     
    value = instance.Remove(column)  
  
C#|   
---|---  
      
    
    public bool Remove( 
       [ProjectCalculationTableColumn](topic3946.md) _column_
    )  
  
#### Parameters

 _column_
    The column to remove.

#### Return Value

True if the column is removed.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ProjectCalculationTableColumns Class](topic3968.md)   
[ProjectCalculationTableColumns Members](topic3969.md)


