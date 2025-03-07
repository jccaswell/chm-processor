Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
CreateTxChangeDocumentName Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Transactions Namespace](topic12835.md) > [ProjectTransactionFactory Class](topic12928.md) : CreateTxChangeDocumentName Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_document_
    The document to change the name of.

_newName_
    The new name to give the document.

Glossary Item Box

Creates a transaction which, when committed, will change the name of the specified document. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function CreateTxChangeDocumentName( _
       ByVal _document_ As [ProjectDocument](topic4356.md), _
       ByVal _newName_ As String _
    ) As [ITransaction](topic12837.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ProjectTransactionFactory](topic12928.md)
    Dim document As [ProjectDocument](topic4356.md)
    Dim newName As String
    Dim value As [ITransaction](topic12837.md)
     
    value = instance.CreateTxChangeDocumentName(document, newName)  
  
C#|   
---|---  
      
    
    public [ITransaction](topic12837.md) CreateTxChangeDocumentName( 
       [ProjectDocument](topic4356.md) _document_ ,
       string _newName_
    )  
  
#### Parameters

 _document_
    The document to change the name of.
_newName_
    The new name to give the document.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ProjectTransactionFactory Class](topic12928.md)   
[ProjectTransactionFactory Members](topic12929.md)


