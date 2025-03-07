Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
CreateTxChangeVariableRule Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Transactions Namespace](topic12835.md) > [ProjectTransactionFactory Class](topic12928.md) : CreateTxChangeVariableRule Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_variable_
    The variable to change.

_newRule_
    The new rule.

Glossary Item Box

Creates a transaction which, when committed, will change the specified variable's rule. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function CreateTxChangeVariableRule( _
       ByVal _variable_ As [ProjectVariable](topic4927.md), _
       ByVal _newRule_ As String _
    ) As [ITransaction](topic12837.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ProjectTransactionFactory](topic12928.md)
    Dim variable As [ProjectVariable](topic4927.md)
    Dim newRule As String
    Dim value As [ITransaction](topic12837.md)
     
    value = instance.CreateTxChangeVariableRule(variable, newRule)  
  
C#|   
---|---  
      
    
    public [ITransaction](topic12837.md) CreateTxChangeVariableRule( 
       [ProjectVariable](topic4927.md) _variable_ ,
       string _newRule_
    )  
  
#### Parameters

 _variable_
    The variable to change.
_newRule_
    The new rule.

#### Return Value

A transaction which, when executed, will perform the operation.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ProjectTransactionFactory Class](topic12928.md)   
[ProjectTransactionFactory Members](topic12929.md)


