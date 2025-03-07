SolidWorksOperationPriority Enumeration   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications.Autopilot.Extensibility Namespace](topic1633.md) : SolidWorksOperationPriority Enumeration  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Represents the relative priority of an operation being coordinated by the [ISolidWorksHealthMonitor](topic1741.md). 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Enum SolidWorksOperationPriority 
       Inherits System.Enum  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [SolidWorksOperationPriority](topic1808.md)  
  
C#|   
---|---  
      
    
    public enum SolidWorksOperationPriority : System.Enum   
  
# Members

Member| Description  
---|---  
**Immediate**|  The operation requires immediate processing.  
**Normal**|  The operation should be queued behind any others.  
  
# Inheritance Hierarchy

System.Object  
System.ValueType  
System.Enum  
**DriveWorks.Applications.Autopilot.Extensibility.SolidWorksOperationPriority**  


# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[DriveWorks.Applications.Autopilot.Extensibility Namespace](topic1633.md)


