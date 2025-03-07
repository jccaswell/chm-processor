Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
CreateTxRenameProjetComponentSet Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Transactions Namespace](topic12835.md) > [ProjectTransactionFactory Class](topic12928.md) : CreateTxRenameProjetComponentSet Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_oldName_
    The current name of the component set to rename.

_newName_
    The new name to apply to the component set.

Glossary Item Box

Creates a transaction that will rename a component set. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function CreateTxRenameProjetComponentSet( _
       ByVal _oldName_ As String, _
       ByVal _newName_ As String _
    ) As [ITransaction](topic12837.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ProjectTransactionFactory](topic12928.md)
    Dim oldName As String
    Dim newName As String
    Dim value As [ITransaction](topic12837.md)
     
    value = instance.CreateTxRenameProjetComponentSet(oldName, newName)  
  
C#|   
---|---  
      
    
    public [ITransaction](topic12837.md) CreateTxRenameProjetComponentSet( 
       string _oldName_ ,
       string _newName_
    )  
  
#### Parameters

 _oldName_
    The current name of the component set to rename.
_newName_
    The new name to apply to the component set.

#### Return Value

A transaction that will perform the operation.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ProjectTransactionFactory Class](topic12928.md)   
[ProjectTransactionFactory Members](topic12929.md)


