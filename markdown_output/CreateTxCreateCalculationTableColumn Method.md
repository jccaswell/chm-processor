Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
CreateTxCreateCalculationTableColumn Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Transactions Namespace](topic12835.md) > [ProjectTransactionFactory Class](topic12928.md) : CreateTxCreateCalculationTableColumn Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_tableName_
    The name of the table to use.

_columnName_
    The name of the column to use.

_columnType_
    The column type to create.

Glossary Item Box

Creates a transaction that will create a calculation table column. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function CreateTxCreateCalculationTableColumn( _
       ByVal _tableName_ As String, _
       ByVal _columnName_ As String, _
       ByVal _columnType_ As [ProjectCalculationTableColumnType](topic2356.md) _
    ) As [ITransaction](topic12837.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ProjectTransactionFactory](topic12928.md)
    Dim tableName As String
    Dim columnName As String
    Dim columnType As [ProjectCalculationTableColumnType](topic2356.md)
    Dim value As [ITransaction](topic12837.md)
     
    value = instance.CreateTxCreateCalculationTableColumn(tableName, columnName, columnType)  
  
C#|   
---|---  
      
    
    public [ITransaction](topic12837.md) CreateTxCreateCalculationTableColumn( 
       string _tableName_ ,
       string _columnName_ ,
       [ProjectCalculationTableColumnType](topic2356.md) _columnType_
    )  
  
#### Parameters

 _tableName_
    The name of the table to use.
_columnName_
    The name of the column to use.
_columnType_
    The column type to create.

#### Return Value

A transaction that will perform the operation.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ProjectTransactionFactory Class](topic12928.md)   
[ProjectTransactionFactory Members](topic12929.md)


