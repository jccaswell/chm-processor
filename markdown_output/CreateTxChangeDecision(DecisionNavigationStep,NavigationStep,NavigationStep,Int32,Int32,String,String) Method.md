Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
CreateTxChangeDecision(DecisionNavigationStep,NavigationStep,NavigationStep,Int32,Int32,String,String) Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Transactions Namespace](topic12835.md) > [ProjectTransactionFactory Class](topic12928.md) > [CreateTxChangeDecision Method](topic12962.md) : CreateTxChangeDecision(DecisionNavigationStep,NavigationStep,NavigationStep,Int32,Int32,String,String) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_decision_
    The decision to update.

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

_comment_
    The comment for the rule

Glossary Item Box

Creates a transaction which, when committed, will update a decision with the given name to the given properties, only project and name are needed 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Overloads Function CreateTxChangeDecision( _
       ByVal _decision_ As [DecisionNavigationStep](topic10125.md), _
       ByVal _nextStepTrue_ As [NavigationStep](topic10175.md), _
       ByVal _nextStepFalse_ As [NavigationStep](topic10175.md), _
       ByVal _left_ As Integer, _
       ByVal _top_ As Integer, _
       ByVal _conditionExpression_ As String, _
       ByVal _comment_ As String _
    ) As [ITransaction](topic12837.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ProjectTransactionFactory](topic12928.md)
    Dim decision As [DecisionNavigationStep](topic10125.md)
    Dim nextStepTrue As [NavigationStep](topic10175.md)
    Dim nextStepFalse As [NavigationStep](topic10175.md)
    Dim left As Integer
    Dim top As Integer
    Dim conditionExpression As String
    Dim comment As String
    Dim value As [ITransaction](topic12837.md)
     
    value = instance.CreateTxChangeDecision(decision, nextStepTrue, nextStepFalse, left, top, conditionExpression, comment)  
  
C#|   
---|---  
      
    
    public [ITransaction](topic12837.md) CreateTxChangeDecision( 
       [DecisionNavigationStep](topic10125.md) _decision_ ,
       [NavigationStep](topic10175.md) _nextStepTrue_ ,
       [NavigationStep](topic10175.md) _nextStepFalse_ ,
       int _left_ ,
       int _top_ ,
       string _conditionExpression_ ,
       string _comment_
    )  
  
#### Parameters

 _decision_
    The decision to update.
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
_comment_
    The comment for the rule

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ProjectTransactionFactory Class](topic12928.md)   
[ProjectTransactionFactory Members](topic12929.md)   
[Overload List](topic12962.md)


