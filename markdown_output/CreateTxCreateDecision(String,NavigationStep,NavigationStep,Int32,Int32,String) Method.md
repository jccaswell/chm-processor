Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
CreateTxCreateDecision(String,NavigationStep,NavigationStep,Int32,Int32,String) Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Transactions Namespace](topic12835.md) > [ProjectTransactionFactory Class](topic12928.md) > [CreateTxCreateDecision Method](topic13045.md) : CreateTxCreateDecision(String,NavigationStep,NavigationStep,Int32,Int32,String) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_name_
    The name of the new decision.

_nextStepTrue_
    The next step, should the condition expression return true.

_nextStepFalse_
    The next step, should the condition expression return false.

_left_
    The horrizontal position of the decision.

_top_
    The vertical position of the decision.

_conditionExpression_
    The condition expression of the decision.

Glossary Item Box

Creates a transaction which, when committed, will create a decision with the given properties, name is the only needed property. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Overloads Function CreateTxCreateDecision( _
       ByVal _name_ As String, _
       ByVal _nextStepTrue_ As [NavigationStep](topic10175.md), _
       ByVal _nextStepFalse_ As [NavigationStep](topic10175.md), _
       ByVal _left_ As Integer, _
       ByVal _top_ As Integer, _
       ByVal _conditionExpression_ As String _
    ) As [ITransaction](topic12837.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ProjectTransactionFactory](topic12928.md)
    Dim name As String
    Dim nextStepTrue As [NavigationStep](topic10175.md)
    Dim nextStepFalse As [NavigationStep](topic10175.md)
    Dim left As Integer
    Dim top As Integer
    Dim conditionExpression As String
    Dim value As [ITransaction](topic12837.md)
     
    value = instance.CreateTxCreateDecision(name, nextStepTrue, nextStepFalse, left, top, conditionExpression)  
  
C#|   
---|---  
      
    
    public [ITransaction](topic12837.md) CreateTxCreateDecision( 
       string _name_ ,
       [NavigationStep](topic10175.md) _nextStepTrue_ ,
       [NavigationStep](topic10175.md) _nextStepFalse_ ,
       int _left_ ,
       int _top_ ,
       string _conditionExpression_
    )  
  
#### Parameters

 _name_
    The name of the new decision.
_nextStepTrue_
    The next step, should the condition expression return true.
_nextStepFalse_
    The next step, should the condition expression return false.
_left_
    The horrizontal position of the decision.
_top_
    The vertical position of the decision.
_conditionExpression_
    The condition expression of the decision.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ProjectTransactionFactory Class](topic12928.md)   
[ProjectTransactionFactory Members](topic12929.md)   
[Overload List](topic13045.md)


