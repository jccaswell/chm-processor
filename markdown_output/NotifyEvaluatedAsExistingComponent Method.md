Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
NotifyEvaluatedAsExistingComponent Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Components Namespace](topic6089.md) > [IReleaseTracker Interface](topic6119.md) : NotifyEvaluatedAsExistingComponent Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_existingComponentId_
    The unique identifier of the existing component.

_existingComponentPath_
    The full path to the existing component.

Glossary Item Box

Called when the current component is determined to have already been evaluated. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Sub NotifyEvaluatedAsExistingComponent( _
       ByVal _existingComponentId_ As Guid, _
       ByVal _existingComponentPath_ As String _
    )   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [IReleaseTracker](topic6119.md)
    Dim existingComponentId As Guid
    Dim existingComponentPath As String
     
    instance.NotifyEvaluatedAsExistingComponent(existingComponentId, existingComponentPath)  
  
C#|   
---|---  
      
    
    void NotifyEvaluatedAsExistingComponent( 
       Guid _existingComponentId_ ,
       string _existingComponentPath_
    )  
  
#### Parameters

 _existingComponentId_
    The unique identifier of the existing component.
_existingComponentPath_
    The full path to the existing component.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[IReleaseTracker Interface](topic6119.md)   
[IReleaseTracker Members](topic6120.md)


