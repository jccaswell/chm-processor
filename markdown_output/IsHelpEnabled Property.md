Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
IsHelpEnabled Property   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications Namespace](topic16.md) > [WizardBase Class](topic1200.md) : IsHelpEnabled Property  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Determines if the help button is enabled, the default implementation checks to see if the wizard implements the [IHasHelp](topic288.md) interface. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Protected Overridable ReadOnly Property IsHelpEnabled As Boolean  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [WizardBase](topic1200.md)
    Dim value As Boolean
     
    value = instance.IsHelpEnabled  
  
C#|   
---|---  
      
    
    protected virtual bool IsHelpEnabled {get;}  
  
# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[WizardBase Class](topic1200.md)   
[WizardBase Members](topic1201.md)


