Text Property   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Rules Namespace](topic10510.md) > [IRuleNode Interface](topic10542.md) : Text Property  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

The inner text value for this node. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    ReadOnly Property Text As String  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [IRuleNode](topic10542.md)
    Dim value As String
     
    value = instance.Text  
  
C#|   
---|---  
      
    
    string Text {get;}  
  
# Remarks

The inner text is the text of the node without its arguments, for example the inner text for an operator would be the operator, and for an IF statement it would be the word IF.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[IRuleNode Interface](topic10542.md)   
[IRuleNode Members](topic10543.md)


