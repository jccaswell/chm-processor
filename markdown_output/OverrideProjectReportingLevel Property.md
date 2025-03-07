Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
OverrideProjectReportingLevel Property   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Specification Namespace](topic10764.md) > [SpecificationEnvironment Class](topic11355.md) : OverrideProjectReportingLevel Property  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Gets/sets whether the reporting level set on the environment should override the equivalent level set on the project. This is automatically set to true if the reporting level is changed on the environment. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Property OverrideProjectReportingLevel As Boolean  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [SpecificationEnvironment](topic11355.md)
    Dim value As Boolean
     
    instance.OverrideProjectReportingLevel = value
     
    value = instance.OverrideProjectReportingLevel  
  
C#|   
---|---  
      
    
    public bool OverrideProjectReportingLevel {get; set;}  
  
# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[SpecificationEnvironment Class](topic11355.md)   
[SpecificationEnvironment Members](topic11356.md)


