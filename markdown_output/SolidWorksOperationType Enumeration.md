SolidWorksOperationType Enumeration   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications.Autopilot.Extensibility Namespace](topic1633.md) : SolidWorksOperationType Enumeration  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Indicates the type of an operation being coordinated by the [ISolidWorksHealthMonitor](topic1741.md). 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Enum SolidWorksOperationType 
       Inherits System.Enum  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [SolidWorksOperationType](topic1809.md)  
  
C#|   
---|---  
      
    
    public enum SolidWorksOperationType : System.Enum   
  
# Members

Member| Description  
---|---  
**Other**|  The operation is going to generate a model for some other reason.  
**PreviewModel**|  The operation is going to generate a model for a preview.  
**SpecificationModel**|  The operation is going to generate a model for a specification.  
  
# Inheritance Hierarchy

System.Object  
System.ValueType  
System.Enum  
**DriveWorks.Applications.Autopilot.Extensibility.SolidWorksOperationType**  


# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[DriveWorks.Applications.Autopilot.Extensibility Namespace](topic1633.md)


