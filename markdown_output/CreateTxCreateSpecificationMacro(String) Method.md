Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
CreateTxCreateSpecificationMacro(String) Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Transactions Namespace](topic12835.md) > [ProjectTransactionFactory Class](topic12928.md) > [CreateTxCreateSpecificationMacro Method](topic13059.md) : CreateTxCreateSpecificationMacro(String) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_name_
    The name of the new specification macro.

Glossary Item Box

Creates a transaction which when committed will create a specification macro with the given name. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Overloads Function CreateTxCreateSpecificationMacro( _
       ByVal _name_ As String _
    ) As [ITransaction](topic12837.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ProjectTransactionFactory](topic12928.md)
    Dim name As String
    Dim value As [ITransaction](topic12837.md)
     
    value = instance.CreateTxCreateSpecificationMacro(name)  
  
C#|   
---|---  
      
    
    public [ITransaction](topic12837.md) CreateTxCreateSpecificationMacro( 
       string _name_
    )  
  
#### Parameters

 _name_
    The name of the new specification macro.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ProjectTransactionFactory Class](topic12928.md)   
[ProjectTransactionFactory Members](topic12929.md)   
[Overload List](topic13059.md)


