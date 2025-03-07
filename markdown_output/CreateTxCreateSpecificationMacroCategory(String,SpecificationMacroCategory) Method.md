Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
CreateTxCreateSpecificationMacroCategory(String,SpecificationMacroCategory) Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Transactions Namespace](topic12835.md) > [ProjectTransactionFactory Class](topic12928.md) > [CreateTxCreateSpecificationMacroCategory Method](topic13062.md) : CreateTxCreateSpecificationMacroCategory(String,SpecificationMacroCategory) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_displayName_
    The display name of the new category.

_parentCategory_
    Optionally, the parent category, or a null reference to leave the category rooted.

Glossary Item Box

Creates a transaction which when committed will create a new specification macro category. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Overloads Function CreateTxCreateSpecificationMacroCategory( _
       ByVal _displayName_ As String, _
       ByVal _parentCategory_ As [SpecificationMacroCategory](topic5359.md) _
    ) As [ITransaction](topic12837.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ProjectTransactionFactory](topic12928.md)
    Dim displayName As String
    Dim parentCategory As [SpecificationMacroCategory](topic5359.md)
    Dim value As [ITransaction](topic12837.md)
     
    value = instance.CreateTxCreateSpecificationMacroCategory(displayName, parentCategory)  
  
C#|   
---|---  
      
    
    public [ITransaction](topic12837.md) CreateTxCreateSpecificationMacroCategory( 
       string _displayName_ ,
       [SpecificationMacroCategory](topic5359.md) _parentCategory_
    )  
  
#### Parameters

 _displayName_
    The display name of the new category.
_parentCategory_
    Optionally, the parent category, or a null reference to leave the category rooted.

#### Return Value

A transaction which, when executed, will perform the operation.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ProjectTransactionFactory Class](topic12928.md)   
[ProjectTransactionFactory Members](topic12929.md)   
[Overload List](topic13062.md)


