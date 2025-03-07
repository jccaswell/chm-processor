Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
NextStep Property   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Navigation Namespace](topic10114.md) > [DecisionNavigationStep Class](topic10125.md) : NextStep Property  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Overridden to throw an exception if it is attempted to change the next step as a decision's next step is governed by the [ConditionExpression](topic10137.md), [NextStepIfTrue](topic10141.md), and [NextStepIfFalse](topic10140.md) properties. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Overrides NotOverridable Property NextStep As [NavigationStep](topic10175.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [DecisionNavigationStep](topic10125.md)
    Dim value As [NavigationStep](topic10175.md)
     
    instance.NextStep = value
     
    value = instance.NextStep  
  
C#|   
---|---  
      
    
    public override [NavigationStep](topic10175.md) NextStep {get; set;}  
  
#### Property Value

The current next step based on the result of calculating the [ConditionExpression](topic10137.md) property.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[DecisionNavigationStep Class](topic10125.md)   
[DecisionNavigationStep Members](topic10126.md)


