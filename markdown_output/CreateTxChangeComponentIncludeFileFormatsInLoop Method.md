Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
CreateTxChangeComponentIncludeFileFormatsInLoop Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Transactions Namespace](topic12835.md) > [ProjectTransactionFactory Class](topic12928.md) : CreateTxChangeComponentIncludeFileFormatsInLoop Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_component_
    The component whose additional file formats will be released in the loop.

_include_
    True to include file formats in the release loop.

Glossary Item Box

Creates a new transaction that when executed will enable generation of additional file formats within the release loop. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function CreateTxChangeComponentIncludeFileFormatsInLoop( _
       ByVal _component_ As [ProjectComponent](topic6183.md), _
       ByVal _include_ As Boolean _
    ) As [ITransaction](topic12837.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ProjectTransactionFactory](topic12928.md)
    Dim component As [ProjectComponent](topic6183.md)
    Dim include As Boolean
    Dim value As [ITransaction](topic12837.md)
     
    value = instance.CreateTxChangeComponentIncludeFileFormatsInLoop(component, include)  
  
C#|   
---|---  
      
    
    public [ITransaction](topic12837.md) CreateTxChangeComponentIncludeFileFormatsInLoop( 
       [ProjectComponent](topic6183.md) _component_ ,
       bool _include_
    )  
  
#### Parameters

 _component_
    The component whose additional file formats will be released in the loop.
_include_
    True to include file formats in the release loop.

#### Return Value

A new transaction that when executed will ensure file formats are generated inside of the release loop.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ProjectTransactionFactory Class](topic12928.md)   
[ProjectTransactionFactory Members](topic12929.md)


