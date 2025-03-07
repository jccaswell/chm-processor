Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
AdditionalState Property   
  
[DriveWorks.SolidWorks Assembly](topic13342.md) > [DriveWorks.SolidWorks.Components Namespace](topic13925.md) > [ReleasedFeature Class](topic14875.md) : AdditionalState Property  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Gets/sets optional additional state information, for example, for most features this is the color information, and for wizard hole features it can be a subset of the hole wizard control parameters. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Property AdditionalState As String  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ReleasedFeature](topic14875.md)
    Dim value As String
     
    instance.AdditionalState = value
     
    value = instance.AdditionalState  
  
C#|   
---|---  
      
    
    public string AdditionalState {get; set;}  
  
# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ReleasedFeature Class](topic14875.md)   
[ReleasedFeature Members](topic14876.md)


