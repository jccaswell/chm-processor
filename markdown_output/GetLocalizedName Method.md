Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
GetLocalizedName Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Localization Namespace](topic10015.md) > [RuleLocalizationHelper Class](topic10018.md) : GetLocalizedName Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_invariantName_
    The invariant name to localize.

Glossary Item Box

Gets the localized version of the specified name. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function GetLocalizedName( _
       ByVal _invariantName_ As String _
    ) As String  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [RuleLocalizationHelper](topic10018.md)
    Dim invariantName As String
    Dim value As String
     
    value = instance.GetLocalizedName(invariantName)  
  
C#|   
---|---  
      
    
    public string GetLocalizedName( 
       string _invariantName_
    )  
  
#### Parameters

 _invariantName_
    The invariant name to localize.

#### Return Value

The localized version of the name or the invariant version if no localized version could be found.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[RuleLocalizationHelper Class](topic10018.md)   
[RuleLocalizationHelper Members](topic10019.md)


