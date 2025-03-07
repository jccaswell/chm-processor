SetDriveAppEnabledByAlias Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [GroupProjects Class](topic3190.md) : SetDriveAppEnabledByAlias Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_appAlias_
    The unique alias of the DriveApp to update.

_enabled_
    The new enabled value to update the DriveApp with.

Glossary Item Box

Updates whether a DriveApp is enabled in the group. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function SetDriveAppEnabledByAlias( _
       ByVal _appAlias_ As String, _
       ByVal _enabled_ As Boolean _
    ) As Boolean  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [GroupProjects](topic3190.md)
    Dim appAlias As String
    Dim enabled As Boolean
    Dim value As Boolean
     
    value = instance.SetDriveAppEnabledByAlias(appAlias, enabled)  
  
C#|   
---|---  
      
    
    public bool SetDriveAppEnabledByAlias( 
       string _appAlias_ ,
       bool _enabled_
    )  
  
#### Parameters

 _appAlias_
    The unique alias of the DriveApp to update.
_enabled_
    The new enabled value to update the DriveApp with.

#### Return Value

True if successfully updated.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[GroupProjects Class](topic3190.md)   
[GroupProjects Members](topic3191.md)


