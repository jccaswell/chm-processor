Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
CreateTxChangeCalculationTableRowCount Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Transactions Namespace](topic12835.md) > [ProjectTransactionFactory Class](topic12928.md) : CreateTxChangeCalculationTableRowCount Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_tableName_
    The name of the table to use.

_rowCount_
    The new number of data rows to have the on table.

Glossary Item Box

Creates a transaction that will change a calculation table's row count (number of data rows). 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function CreateTxChangeCalculationTableRowCount( _
       ByVal _tableName_ As String, _
       ByVal _rowCount_ As Integer _
    ) As [ITransaction](topic12837.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ProjectTransactionFactory](topic12928.md)
    Dim tableName As String
    Dim rowCount As Integer
    Dim value As [ITransaction](topic12837.md)
     
    value = instance.CreateTxChangeCalculationTableRowCount(tableName, rowCount)  
  
C#|   
---|---  
      
    
    public [ITransaction](topic12837.md) CreateTxChangeCalculationTableRowCount( 
       string _tableName_ ,
       int _rowCount_
    )  
  
#### Parameters

 _tableName_
    The name of the table to use.
_rowCount_
    The new number of data rows to have the on table.

#### Return Value

A transaction that will perform the operation.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ProjectTransactionFactory Class](topic12928.md)   
[ProjectTransactionFactory Members](topic12929.md)


