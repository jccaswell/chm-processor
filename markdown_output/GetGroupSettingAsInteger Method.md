Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
GetGroupSettingAsInteger Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [Group Class](topic2958.md) : GetGroupSettingAsInteger Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_name_
    The name of the setting to retrieve.

_defaultValue_
    The value to return if the setting isn't present.

Glossary Item Box

Gets the named setting from the group as an Integer. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function GetGroupSettingAsInteger( _
       ByVal _name_ As String, _
       ByVal _defaultValue_ As Integer _
    ) As Integer  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [Group](topic2958.md)
    Dim name As String
    Dim defaultValue As Integer
    Dim value As Integer
     
    value = instance.GetGroupSettingAsInteger(name, defaultValue)  
  
C#|   
---|---  
      
    
    public int GetGroupSettingAsInteger( 
       string _name_ ,
       int _defaultValue_
    )  
  
#### Parameters

 _name_
    The name of the setting to retrieve.
_defaultValue_
    The value to return if the setting isn't present.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[Group Class](topic2958.md)   
[Group Members](topic2959.md)


