Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
IReleaseTracker Interface   
[Members](topic6120.md)   
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Components Namespace](topic6089.md) : IReleaseTracker Interface  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Provides a contract for an object which is used to track the release of components. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Interface IReleaseTracker   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [IReleaseTracker](topic6119.md)  
  
C#|   
---|---  
      
    
    public interface IReleaseTracker   
  
# Remarks

When evaluation of a component begins, it is assigned a unique tracking identifier, which is passed to the [NotifyBeginEvaluate](topic6125.md) method. This identifier can be used to track hierarchy and release information. Also, if the component is evaluated and determined to be a new component (i.e. not an alternative, driven component, or existing component), then the tracking identifier is used as the identifier assigned to the new component when it is registered.

The release tracker gets called in three phases:

  * Component Set Candidacy Evaluation (the NotifyComponentSetXXX methods)
  * Component Reference Evaluation (the NotifyBeginEvaluate, NotifyEndEvaluate, and NotifyEvaluateXXX methods)
  * Component Release



# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[IReleaseTracker Members](topic6120.md)   
[DriveWorks.Components Namespace](topic6089.md)


