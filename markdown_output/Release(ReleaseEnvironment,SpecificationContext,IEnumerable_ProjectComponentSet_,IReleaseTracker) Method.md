Release(ReleaseEnvironment,SpecificationContext,IEnumerable<ProjectComponentSet>,IReleaseTracker) Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Components Namespace](topic6089.md) > [ReleaseComponentHelper Class](topic6275.md) > [Release Method](topic6281.md) : Release(ReleaseEnvironment,SpecificationContext,IEnumerable<ProjectComponentSet>,IReleaseTracker) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_environment_
    The environment which controls the release process.

_context_
    The specification context for which to release components.

_components_
    The components to release.

_tracker_
    An implementation of the [IReleaseTracker](topic6119.md) interface, or a null reference.

Glossary Item Box

Releases the given components. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Overloads Shared Function Release( _
       ByVal _environment_ As [ReleaseEnvironment](topic6379.md), _
       ByVal _context_ As [SpecificationContext](topic11149.md), _
       ByVal _components_ As IEnumerable(Of ProjectComponentSet), _
       ByVal _tracker_ As [IReleaseTracker](topic6119.md) _
    ) As [ReleaseComponentsResults](topic6300.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim environment As [ReleaseEnvironment](topic6379.md)
    Dim context As [SpecificationContext](topic11149.md)
    Dim components As IEnumerable(Of ProjectComponentSet)
    Dim tracker As [IReleaseTracker](topic6119.md)
    Dim value As [ReleaseComponentsResults](topic6300.md)
     
    value = [ReleaseComponentHelper](topic6275.md).Release(environment, context, components, tracker)  
  
C#|   
---|---  
      
    
    public static [ReleaseComponentsResults](topic6300.md) Release( 
       [ReleaseEnvironment](topic6379.md) _environment_ ,
       [SpecificationContext](topic11149.md) _context_ ,
       IEnumerable<ProjectComponentSet> _components_ ,
       [IReleaseTracker](topic6119.md) _tracker_
    )  
  
#### Parameters

 _environment_
    The environment which controls the release process.
_context_
    The specification context for which to release components.
_components_
    The components to release.
_tracker_
    An implementation of the [IReleaseTracker](topic6119.md) interface, or a null reference.

#### Return Value

The release results.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ReleaseComponentHelper Class](topic6275.md)   
[ReleaseComponentHelper Members](topic6276.md)   
[Overload List](topic6281.md)


