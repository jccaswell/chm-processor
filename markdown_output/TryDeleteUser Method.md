TryDeleteUser Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [GroupSecurity Class](topic3282.md) : TryDeleteUser Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_loginName_
    The login name of the user to be deleted.

Glossary Item Box

Deletes the user with the specified login name. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function TryDeleteUser( _
       ByVal _loginName_ As String _
    ) As Boolean  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [GroupSecurity](topic3282.md)
    Dim loginName As String
    Dim value As Boolean
     
    value = instance.TryDeleteUser(loginName)  
  
C#|   
---|---  
      
    
    public bool TryDeleteUser( 
       string _loginName_
    )  
  
#### Parameters

 _loginName_
    The login name of the user to be deleted.

#### Return Value

True if the user was found and deleted, otherwise false.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[GroupSecurity Class](topic3282.md)   
[GroupSecurity Members](topic3283.md)


