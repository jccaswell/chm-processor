Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
CreateTxSetCalculationTableOutputControlRules Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Transactions Namespace](topic12835.md) > [ProjectTransactionFactory Class](topic12928.md) : CreateTxSetCalculationTableOutputControlRules Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_tableName_
    The name of the table to use.

Glossary Item Box

Creates a transaction that will find all controls that can be driven from the specified table and set their rules to point to the table. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function CreateTxSetCalculationTableOutputControlRules( _
       ByVal _tableName_ As String _
    ) As [ITransaction](topic12837.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ProjectTransactionFactory](topic12928.md)
    Dim tableName As String
    Dim value As [ITransaction](topic12837.md)
     
    value = instance.CreateTxSetCalculationTableOutputControlRules(tableName)  
  
C#|   
---|---  
      
    
    public [ITransaction](topic12837.md) CreateTxSetCalculationTableOutputControlRules( 
       string _tableName_
    )  
  
#### Parameters

 _tableName_
    The name of the table to use.

#### Return Value

A transaction that will perform the operation.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ProjectTransactionFactory Class](topic12928.md)   
[ProjectTransactionFactory Members](topic12929.md)


