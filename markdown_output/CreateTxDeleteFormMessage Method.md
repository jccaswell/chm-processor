Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
CreateTxDeleteFormMessage Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Transactions Namespace](topic12835.md) > [ProjectTransactionFactory Class](topic12928.md) : CreateTxDeleteFormMessage Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_formMessage_
    The for message to be deleted.

Glossary Item Box

Creates a transaction which, when committed, will delete a form message. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function CreateTxDeleteFormMessage( _
       ByVal _formMessage_ As [ProjectMessage](topic4601.md) _
    ) As [ITransaction](topic12837.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ProjectTransactionFactory](topic12928.md)
    Dim formMessage As [ProjectMessage](topic4601.md)
    Dim value As [ITransaction](topic12837.md)
     
    value = instance.CreateTxDeleteFormMessage(formMessage)  
  
C#|   
---|---  
      
    
    public [ITransaction](topic12837.md) CreateTxDeleteFormMessage( 
       [ProjectMessage](topic4601.md) _formMessage_
    )  
  
#### Parameters

 _formMessage_
    The for message to be deleted.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ProjectTransactionFactory Class](topic12928.md)   
[ProjectTransactionFactory Members](topic12929.md)


