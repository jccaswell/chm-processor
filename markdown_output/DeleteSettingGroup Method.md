Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
DeleteSettingGroup Method   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications Namespace](topic16.md) > [ISettingsManager Interface](topic442.md) : DeleteSettingGroup Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_level_
    The level at which to delete the setting group.

_groupName_
    The full name of the setting group.

_preventRedirection_
    True to prevent automatic redirection if redirection is turned on.

Glossary Item Box

Deletes the specified setting group. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Sub DeleteSettingGroup( _
       ByVal _level_ As [SettingLevel](topic661.md), _
       ByVal _groupName_ As String, _
       ByVal _preventRedirection_ As Boolean _
    )   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ISettingsManager](topic442.md)
    Dim level As [SettingLevel](topic661.md)
    Dim groupName As String
    Dim preventRedirection As Boolean
     
    instance.DeleteSettingGroup(level, groupName, preventRedirection)  
  
C#|   
---|---  
      
    
    void DeleteSettingGroup( 
       [SettingLevel](topic661.md) _level_ ,
       string _groupName_ ,
       bool _preventRedirection_
    )  
  
#### Parameters

 _level_
    The level at which to delete the setting group.
_groupName_
    The full name of the setting group.
_preventRedirection_
    True to prevent automatic redirection if redirection is turned on.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ISettingsManager Interface](topic442.md)   
[ISettingsManager Members](topic443.md)


