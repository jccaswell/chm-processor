UpdateLine Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [TextDocumentLine Class](topic5659.md) : UpdateLine Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_rule_
    The new rule for the line.

_comment_
    The new comment for the line's rule.

_value_
    The calculated value of the new rule.

Glossary Item Box

Updates the rule, comment and value for this line. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Sub UpdateLine( _
       ByVal _rule_ As String, _
       ByVal _comment_ As String, _
       ByVal _value_ As String _
    )   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [TextDocumentLine](topic5659.md)
    Dim rule As String
    Dim comment As String
    Dim value As String
     
    instance.UpdateLine(rule, comment, value)  
  
C#|   
---|---  
      
    
    public void UpdateLine( 
       string _rule_ ,
       string _comment_ ,
       string _value_
    )  
  
#### Parameters

 _rule_
    The new rule for the line.
_comment_
    The new comment for the line's rule.
_value_
    The calculated value of the new rule.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[TextDocumentLine Class](topic5659.md)   
[TextDocumentLine Members](topic5660.md)


