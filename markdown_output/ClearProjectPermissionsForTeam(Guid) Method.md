Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
ClearProjectPermissionsForTeam(Guid) Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [GroupSecurity Class](topic3282.md) > [ClearProjectPermissionsForTeam Method](topic3292.md) : ClearProjectPermissionsForTeam(Guid) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_teamId_
    The unique identifier of the team to operate on.

Glossary Item Box

Clears the list of allowed projects for the specified team. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Overloads Sub ClearProjectPermissionsForTeam( _
       ByVal _teamId_ As Guid _
    )   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [GroupSecurity](topic3282.md)
    Dim teamId As Guid
     
    instance.ClearProjectPermissionsForTeam(teamId)  
  
C#|   
---|---  
      
    
    public void ClearProjectPermissionsForTeam( 
       Guid _teamId_
    )  
  
#### Parameters

 _teamId_
    The unique identifier of the team to operate on.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[GroupSecurity Class](topic3282.md)   
[GroupSecurity Members](topic3283.md)   
[Overload List](topic3292.md)


