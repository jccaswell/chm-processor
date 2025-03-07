Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
NavigationStepEventArgs Constructor   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Navigation Namespace](topic10114.md) > [NavigationStepEventArgs Class](topic10205.md) : NavigationStepEventArgs Constructor  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_navigationStep_
    The navigation step that was changed.

Glossary Item Box

Initializes a new instance of the [NavigationStepEventArgs](topic10205.md) type. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function New( _
       ByVal _navigationStep_ As [NavigationStep](topic10175.md) _
    )  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim navigationStep As [NavigationStep](topic10175.md)
     
    Dim instance As New [NavigationStepEventArgs](topic10205.md)(navigationStep)  
  
C#|   
---|---  
      
    
    public NavigationStepEventArgs( 
       [NavigationStep](topic10175.md) _navigationStep_
    )  
  
#### Parameters

 _navigationStep_
    The navigation step that was changed.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[NavigationStepEventArgs Class](topic10205.md)   
[NavigationStepEventArgs Members](topic10206.md)


