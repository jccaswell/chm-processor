Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
PropertyBehavior Enumeration   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Forms.DataModel Namespace](topic9371.md) : PropertyBehavior Enumeration  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Controls the dynamic behavior of a property. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    <FlagsAttribute()>
    Public Enum PropertyBehavior 
       Inherits System.Enum  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [PropertyBehavior](topic9383.md)  
  
C#|   
---|---  
      
    
    [FlagsAttribute()]
    public enum PropertyBehavior : System.Enum   
  
# Members

Member| Description  
---|---  
**FlagDynamicAllowed**|  Determines whether the property is allowed to be dynamic.  
**FlagDynamicDefault**|  Determines whether the default state of the property is to be dynamic.  
**FlagHideFromDesigners**|  Determines whether a property should be hidden from designers.  
**FlagInvariantConversion**|  Determines whether store value conversions will be performed using the invariant culture.  
**FlagNoRuleAllowed**|  Determines whether the property is allowed to have a rule.  
**FlagPreventSourceMerge**|  Determines whether a property stored in the [StandardStoreOptions.Value](topic9384.md) store should be merged with the [StandardStoreOptions.Source](topic9384.md) store.  
**FlagStaticAllowed**|  Determines whether the property is allowed to be static.  
**StandardOptionDynamicDefault**|  The property is dynamic by default.  
**StandardOptionDynamicDisabled**|  The property is static and is not allowed to be dynamic.  
**StandardOptionDynamicEnforced**|  The property is dynamic by default and can not be made static.  
**StandardOptionDynamicEnforcedNoMerge**|  The property is dynamic by default, can not be made static, and must not be merged with the source value  
**StandardOptionDynamicEnforcedNoRule**|  The property is dynamic by default, can not be made static, and does not and must not have a rule.  
**StandardOptionDynamicManual**|  The property is static by default, but can be manually set to be dynamic.  
  
# Inheritance Hierarchy

System.Object  
System.ValueType  
System.Enum  
**DriveWorks.Forms.DataModel.PropertyBehavior**  


# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[DriveWorks.Forms.DataModel Namespace](topic9371.md)


