SetGroupTablePermissionForTeam Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [GroupSecurity Class](topic3282.md) : SetGroupTablePermissionForTeam Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_teamId_
    The unique identifier of the team to set the permissions for.

_groupTableId_
    The unique identifier of the group table to set the permissions of.

_permission_
    The permissions to set for the specified team and group data table.

Glossary Item Box

Sets the specified permissions for the specified team and group. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Sub SetGroupTablePermissionForTeam( _
       ByVal _teamId_ As Guid, _
       ByVal _groupTableId_ As Guid, _
       ByVal _permission_ As [GroupTablePermission](topic10616.md) _
    )   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [GroupSecurity](topic3282.md)
    Dim teamId As Guid
    Dim groupTableId As Guid
    Dim permission As [GroupTablePermission](topic10616.md)
     
    instance.SetGroupTablePermissionForTeam(teamId, groupTableId, permission)  
  
C#|   
---|---  
      
    
    public void SetGroupTablePermissionForTeam( 
       Guid _teamId_ ,
       Guid _groupTableId_ ,
       [GroupTablePermission](topic10616.md) _permission_
    )  
  
#### Parameters

 _teamId_
    The unique identifier of the team to set the permissions for.
_groupTableId_
    The unique identifier of the group table to set the permissions of.
_permission_
    The permissions to set for the specified team and group data table.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[GroupSecurity Class](topic3282.md)   
[GroupSecurity Members](topic3283.md)


