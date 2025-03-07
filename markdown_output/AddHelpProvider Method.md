Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
AddHelpProvider Method   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications.Administrator.Extensibility.RulesBuilder Namespace](topic1581.md) > [IRulesBuilderService Interface](topic1598.md) : AddHelpProvider Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_provider_
    The provider to add.

Glossary Item Box

Adds an inline help provider. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Sub AddHelpProvider( _
       ByVal _provider_ As [IRuleHelpProvider](topic1583.md) _
    )   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [IRulesBuilderService](topic1598.md)
    Dim provider As [IRuleHelpProvider](topic1583.md)
     
    instance.AddHelpProvider(provider)  
  
C#|   
---|---  
      
    
    void AddHelpProvider( 
       [IRuleHelpProvider](topic1583.md) _provider_
    )  
  
#### Parameters

 _provider_
    The provider to add.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[IRulesBuilderService Interface](topic1598.md)   
[IRulesBuilderService Members](topic1599.md)


