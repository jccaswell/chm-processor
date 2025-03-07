ReleasedComponentFlags Enumeration   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Components Namespace](topic6089.md) : ReleasedComponentFlags Enumeration  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Specifies additional behaviour for [ReleasedComponent](topic6324.md)s. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    <FlagsAttribute()>
    Public Enum ReleasedComponentFlags 
       Inherits System.Enum  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ReleasedComponentFlags](topic6145.md)  
  
C#|   
---|---  
      
    
    [FlagsAttribute()]
    public enum ReleasedComponentFlags : System.Enum   
  
# Members

Member| Description  
---|---  
**AwaitingPreview**|  Flags a component as needing a 3d preview creating for it.  
**Deferred**|  Flags a component to be ineligible for generation until this flag gets toggled off.  
**ForceOverwrite**|  Flags a component for overwrite so that if the component has not been marked as generated but the file exist, the file will be regenerated.  
**None**|  No additional behaviour or status has been attached to the component.  
**Previewed**|  Flags a component as being attempted via a preview.  
  
# Inheritance Hierarchy

System.Object  
System.ValueType  
System.Enum  
**DriveWorks.Components.ReleasedComponentFlags**  


# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[DriveWorks.Components Namespace](topic6089.md)


