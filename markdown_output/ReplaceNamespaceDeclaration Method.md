ReplaceNamespaceDeclaration Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [AdvancedXmlDocument Class](topic2364.md) : ReplaceNamespaceDeclaration Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_element_
    

_nsPrefix_
    

_nsUri_
    

Glossary Item Box

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Protected Sub ReplaceNamespaceDeclaration( _
       ByRef _element_ As XElement, _
       ByVal _nsPrefix_ As String, _
       ByVal _nsUri_ As String _
    )   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [AdvancedXmlDocument](topic2364.md)
    Dim element As XElement
    Dim nsPrefix As String
    Dim nsUri As String
     
    instance.ReplaceNamespaceDeclaration(element, nsPrefix, nsUri)  
  
C#|   
---|---  
      
    
    protected void ReplaceNamespaceDeclaration( 
       ref XElement _element_ ,
       string _nsPrefix_ ,
       string _nsUri_
    )  
  
#### Parameters

 _element_
    
_nsPrefix_
    
_nsUri_
    

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[AdvancedXmlDocument Class](topic2364.md)   
[AdvancedXmlDocument Members](topic2365.md)


