Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
QueryTransition Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Specification Namespace](topic10764.md) > [SpecificationContext Class](topic11149.md) : QueryTransition Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_transitionName_
    The name of the transition to query.

Glossary Item Box

Queries an transition's tasks for confirmation messages that should be shown to an interactive user before invoking the transition. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function QueryTransition( _
       ByVal _transitionName_ As String _
    ) As String()  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [SpecificationContext](topic11149.md)
    Dim transitionName As String
    Dim value() As String
     
    value = instance.QueryTransition(transitionName)  
  
C#|   
---|---  
      
    
    public string[] QueryTransition( 
       string _transitionName_
    )  
  
#### Parameters

 _transitionName_
    The name of the transition to query.

#### Return Value

An array of messages, e.g. "Specification x will be deleted", if no messages are collected, an empty array is returned

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[SpecificationContext Class](topic11149.md)   
[SpecificationContext Members](topic11150.md)


