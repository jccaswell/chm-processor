Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
CreateTxRenameCalculationTableColumn Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Transactions Namespace](topic12835.md) > [ProjectTransactionFactory Class](topic12928.md) : CreateTxRenameCalculationTableColumn Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_tableName_
    The name of the table to use.

_columnName_
    The name of the column to use.

_newColumnName_
    The new name of the column.

Glossary Item Box

Creates a transaction that will rename a calculation table column. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function CreateTxRenameCalculationTableColumn( _
       ByVal _tableName_ As String, _
       ByVal _columnName_ As String, _
       ByVal _newColumnName_ As String _
    ) As [ITransaction](topic12837.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ProjectTransactionFactory](topic12928.md)
    Dim tableName As String
    Dim columnName As String
    Dim newColumnName As String
    Dim value As [ITransaction](topic12837.md)
     
    value = instance.CreateTxRenameCalculationTableColumn(tableName, columnName, newColumnName)  
  
C#|   
---|---  
      
    
    public [ITransaction](topic12837.md) CreateTxRenameCalculationTableColumn( 
       string _tableName_ ,
       string _columnName_ ,
       string _newColumnName_
    )  
  
#### Parameters

 _tableName_
    The name of the table to use.
_columnName_
    The name of the column to use.
_newColumnName_
    The new name of the column.

#### Return Value

A transaction that will perform the operation.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ProjectTransactionFactory Class](topic12928.md)   
[ProjectTransactionFactory Members](topic12929.md)


