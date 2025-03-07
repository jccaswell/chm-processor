Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
CreateTxCreateOperation Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Transactions Namespace](topic12835.md) > [ProjectTransactionFactory Class](topic12928.md) : CreateTxCreateOperation Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_stateTitle_
    The state to create this operation in.

_name_
    The name and title of the new operation

Glossary Item Box

Creates a transaction which, when committed, will create an operation with given name on the given state. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function CreateTxCreateOperation( _
       ByVal _stateTitle_ As String, _
       ByVal _name_ As String _
    ) As [ITransaction](topic12837.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ProjectTransactionFactory](topic12928.md)
    Dim stateTitle As String
    Dim name As String
    Dim value As [ITransaction](topic12837.md)
     
    value = instance.CreateTxCreateOperation(stateTitle, name)  
  
C#|   
---|---  
      
    
    public [ITransaction](topic12837.md) CreateTxCreateOperation( 
       string _stateTitle_ ,
       string _name_
    )  
  
#### Parameters

 _stateTitle_
    The state to create this operation in.
_name_
    The name and title of the new operation

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ProjectTransactionFactory Class](topic12928.md)   
[ProjectTransactionFactory Members](topic12929.md)


