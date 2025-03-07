Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
CreateTxCreateConstant(String,Object,String) Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Transactions Namespace](topic12835.md) > [ProjectTransactionFactory Class](topic12928.md) > [CreateTxCreateConstant Method](topic13038.md) : CreateTxCreateConstant(String,Object,String) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_displayName_
    The display name of the new constant.

_value_
    Optionally, the value to apply to the constant.

_comment_
    Optionally, the comment to apply to the constant.

Glossary Item Box

Creates a transaction which, when committed, will create a constant with the given display name, and optionally, value. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Overloads Function CreateTxCreateConstant( _
       ByVal _displayName_ As String, _
       ByVal _value_ As Object, _
       ByVal _comment_ As String _
    ) As [ITransaction](topic12837.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ProjectTransactionFactory](topic12928.md)
    Dim displayName As String
    Dim value As Object
    Dim comment As String
    Dim value As [ITransaction](topic12837.md)
     
    value = instance.CreateTxCreateConstant(displayName, value, comment)  
  
C#|   
---|---  
      
    
    public [ITransaction](topic12837.md) CreateTxCreateConstant( 
       string _displayName_ ,
       object _value_ ,
       string _comment_
    )  
  
#### Parameters

 _displayName_
    The display name of the new constant.
_value_
    Optionally, the value to apply to the constant.
_comment_
    Optionally, the comment to apply to the constant.

#### Return Value

A transaction which, when executed, will perform the operation.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ProjectTransactionFactory Class](topic12928.md)   
[ProjectTransactionFactory Members](topic12929.md)   
[Overload List](topic13038.md)


