Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
FromTransition Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Transactions Namespace](topic12835.md) > [TaskSequenceRef Class](topic13159.md) : FromTransition Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_transition_
    The transition for which to construct the reference.

Glossary Item Box

Constructs a task sequence reference for the given transition. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Shared Function FromTransition( _
       ByVal _transition_ As [Transition](topic11757.md) _
    ) As [TaskSequenceRef](topic13159.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim transition As [Transition](topic11757.md)
    Dim value As [TaskSequenceRef](topic13159.md)
     
    value = [TaskSequenceRef](topic13159.md).FromTransition(transition)  
  
C#|   
---|---  
      
    
    public static [TaskSequenceRef](topic13159.md) FromTransition( 
       [Transition](topic11757.md) _transition_
    )  
  
#### Parameters

 _transition_
    The transition for which to construct the reference.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[TaskSequenceRef Class](topic13159.md)   
[TaskSequenceRef Members](topic13160.md)


