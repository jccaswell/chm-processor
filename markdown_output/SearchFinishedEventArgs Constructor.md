SearchFinishedEventArgs Constructor   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Refactoring Namespace](topic10266.md) > [SearchFinishedEventArgs Class](topic10317.md) : SearchFinishedEventArgs Constructor  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_names_
    The names we searched for.

_uses_
    All uses in rules of the name we searched for.

Glossary Item Box

Initializes a new instance of the [SearchFinishedEventArgs](topic10317.md) class. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function New( _
       ByVal _names_() As String, _
       ByVal _uses_() As [RuleSearchResult](topic13227.md) _
    )  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim names() As String
    Dim uses() As [RuleSearchResult](topic13227.md)
     
    Dim instance As New [SearchFinishedEventArgs](topic10317.md)(names, uses)  
  
C#|   
---|---  
      
    
    public SearchFinishedEventArgs( 
       string[] _names_ ,
       [RuleSearchResult](topic13227.md)[] _uses_
    )  
  
#### Parameters

 _names_
    The names we searched for.
_uses_
    All uses in rules of the name we searched for.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[SearchFinishedEventArgs Class](topic10317.md)   
[SearchFinishedEventArgs Members](topic10318.md)


