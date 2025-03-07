Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
Authenticate Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Security Namespace](topic10574.md) > [IAuthenticationProvider Interface](topic10576.md) : Authenticate Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_credentials_
    The credentials to authenticate.

Glossary Item Box

Authenticates the given credentials and returns the relevant principal. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Function Authenticate( _
       ByVal _credentials_ As [IProviderCredentials](topic10588.md) _
    ) As [IProviderPrincipal](topic10597.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [IAuthenticationProvider](topic10576.md)
    Dim credentials As [IProviderCredentials](topic10588.md)
    Dim value As [IProviderPrincipal](topic10597.md)
     
    value = instance.Authenticate(credentials)  
  
C#|   
---|---  
      
    
    [IProviderPrincipal](topic10597.md) Authenticate( 
       [IProviderCredentials](topic10588.md) _credentials_
    )  
  
#### Parameters

 _credentials_
    The credentials to authenticate.

#### Return Value

An instance of a type derived from [IProviderPrincipal](topic10597.md) which represents the authenticated principal, or a null reference if the credentials are invalid.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[IAuthenticationProvider Interface](topic10576.md)   
[IAuthenticationProvider Members](topic10577.md)


