TagOverrides Property   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Components Namespace](topic6089.md) > [ReleaseEnvironment Class](topic6379.md) : TagOverrides Property  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Gets/sets a list of tags that should be applied to ALL components, thereby overriding their tag rules. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Property TagOverrides As String()  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ReleaseEnvironment](topic6379.md)
    Dim value() As String
     
    instance.TagOverrides = value
     
    value = instance.TagOverrides  
  
C#|   
---|---  
      
    
    public string[] TagOverrides {get; set;}  
  
# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ReleaseEnvironment Class](topic6379.md)   
[ReleaseEnvironment Members](topic6380.md)


