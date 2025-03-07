Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
CreateTxChangeParentConstantCategory(ProjectConstantCategory,ProjectConstantCategory) Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Transactions Namespace](topic12835.md) > [ProjectTransactionFactory Class](topic12928.md) > [CreateTxChangeParentConstantCategory Method](topic12984.md) : CreateTxChangeParentConstantCategory(ProjectConstantCategory,ProjectConstantCategory) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_constantCategory_
    The constant category to modify.

_newParentCategory_
    The new parent category, or a null reference (Nothing in Visual Basic) to remove the parent.

Glossary Item Box

Creates a transaction which, when committed, will change the parent category of the specified constant category. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Overloads Function CreateTxChangeParentConstantCategory( _
       ByVal _constantCategory_ As [ProjectConstantCategory](topic4219.md), _
       ByVal _newParentCategory_ As [ProjectConstantCategory](topic4219.md) _
    ) As [ITransaction](topic12837.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ProjectTransactionFactory](topic12928.md)
    Dim constantCategory As [ProjectConstantCategory](topic4219.md)
    Dim newParentCategory As [ProjectConstantCategory](topic4219.md)
    Dim value As [ITransaction](topic12837.md)
     
    value = instance.CreateTxChangeParentConstantCategory(constantCategory, newParentCategory)  
  
C#|   
---|---  
      
    
    public [ITransaction](topic12837.md) CreateTxChangeParentConstantCategory( 
       [ProjectConstantCategory](topic4219.md) _constantCategory_ ,
       [ProjectConstantCategory](topic4219.md) _newParentCategory_
    )  
  
#### Parameters

 _constantCategory_
    The constant category to modify.
_newParentCategory_
    The new parent category, or a null reference (Nothing in Visual Basic) to remove the parent.

#### Return Value

A transaction which, when executed, will perform the operation.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ProjectTransactionFactory Class](topic12928.md)   
[ProjectTransactionFactory Members](topic12929.md)   
[Overload List](topic12984.md)


