Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
Complete Method   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications.Autopilot.Extensibility Namespace](topic1633.md) > [ISolidWorksOperation Interface](topic1748.md) : Complete Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Notifies the health monitor that the operation has completed successfully. If this method is not called by the time the operation is disposed, the health monitor will assume that something went wrong, and that SolidWorks should likely be restarted. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Sub Complete()   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ISolidWorksOperation](topic1748.md)
     
    instance.Complete()  
  
C#|   
---|---  
      
    
    void Complete()  
  
# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ISolidWorksOperation Interface](topic1748.md)   
[ISolidWorksOperation Members](topic1749.md)


