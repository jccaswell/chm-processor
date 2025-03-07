Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
CreateTxCreateComponentTaskCondition Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Transactions Namespace](topic12835.md) > [ProjectTransactionFactory Class](topic12928.md) : CreateTxCreateComponentTaskCondition Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_component_
    The component of the task on which to create the condition.

_taskName_
    The name of the task to create the condition for.

_type_
    The type of the condition to create.

_title_
    The title to give the newly created condition.

Glossary Item Box

Creates a new transaction that when executes will create a new component task condition. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function CreateTxCreateComponentTaskCondition( _
       ByVal _component_ As [ProjectComponent](topic6183.md), _
       ByVal _taskName_ As String, _
       ByVal _type_ As Type, _
       ByVal _title_ As String _
    ) As [ITransaction](topic12837.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ProjectTransactionFactory](topic12928.md)
    Dim component As [ProjectComponent](topic6183.md)
    Dim taskName As String
    Dim type As Type
    Dim title As String
    Dim value As [ITransaction](topic12837.md)
     
    value = instance.CreateTxCreateComponentTaskCondition(component, taskName, type, title)  
  
C#|   
---|---  
      
    
    public [ITransaction](topic12837.md) CreateTxCreateComponentTaskCondition( 
       [ProjectComponent](topic6183.md) _component_ ,
       string _taskName_ ,
       Type _type_ ,
       string _title_
    )  
  
#### Parameters

 _component_
    The component of the task on which to create the condition.
_taskName_
    The name of the task to create the condition for.
_type_
    The type of the condition to create.
_title_
    The title to give the newly created condition.

#### Return Value

A transaction that when executed will create the condition.

# Exceptions

Exception| Description  
---|---  
System.ArgumentNullException| component, taskName, or type is null.  
  
# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ProjectTransactionFactory Class](topic12928.md)   
[ProjectTransactionFactory Members](topic12929.md)


