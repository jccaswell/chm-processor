Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
Bind(String,String) Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Specification Namespace](topic10764.md) > [FlowProperty Class](topic10946.md) > [Bind Method](topic10952.md) : Bind(String,String) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_rule_
    The rule to apply.

_comment_
    The comment to apply.

Glossary Item Box

Binds the property to a rule. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Overloads Sub Bind( _
       ByVal _rule_ As String, _
       ByVal _comment_ As String _
    )   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [FlowProperty](topic10946.md)
    Dim rule As String
    Dim comment As String
     
    instance.Bind(rule, comment)  
  
C#|   
---|---  
      
    
    public void Bind( 
       string _rule_ ,
       string _comment_
    )  
  
#### Parameters

 _rule_
    The rule to apply.
_comment_
    The comment to apply.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[FlowProperty Class](topic10946.md)   
[FlowProperty Members](topic10947.md)   
[Overload List](topic10952.md)


