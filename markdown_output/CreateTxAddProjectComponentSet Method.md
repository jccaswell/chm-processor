Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
CreateTxAddProjectComponentSet Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Transactions Namespace](topic12835.md) > [ProjectTransactionFactory Class](topic12928.md) : CreateTxAddProjectComponentSet Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_name_
    The name to give the component. This may be null to have one generated from captured component's name.

_capturedComponentId_
    The unique identifier of the captured component that you wish to add to the current project.

Glossary Item Box

Creates a transaction that will add a component to the current project. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function CreateTxAddProjectComponentSet( _
       ByVal _name_ As String, _
       ByVal _capturedComponentId_ As Guid _
    ) As [ITransaction](topic12837.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ProjectTransactionFactory](topic12928.md)
    Dim name As String
    Dim capturedComponentId As Guid
    Dim value As [ITransaction](topic12837.md)
     
    value = instance.CreateTxAddProjectComponentSet(name, capturedComponentId)  
  
C#|   
---|---  
      
    
    public [ITransaction](topic12837.md) CreateTxAddProjectComponentSet( 
       string _name_ ,
       Guid _capturedComponentId_
    )  
  
#### Parameters

 _name_
    The name to give the component. This may be null to have one generated from captured component's name.
_capturedComponentId_
    The unique identifier of the captured component that you wish to add to the current project.

#### Return Value

A transaction that will perform the operation.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ProjectTransactionFactory Class](topic12928.md)   
[ProjectTransactionFactory Members](topic12929.md)


