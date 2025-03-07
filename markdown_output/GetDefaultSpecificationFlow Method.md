Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
GetDefaultSpecificationFlow Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Specification Namespace](topic10764.md) > [SpecificationFlowDefinition Class](topic11387.md) : GetDefaultSpecificationFlow Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_stripComments_
    True to strip comments from the specification flow XML, otherwise false.

Glossary Item Box

Gets the XML representing the default specification flow. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    <EditorBrowsableAttribute(EditorBrowsableState.Advanced)>
    Public Shared Function GetDefaultSpecificationFlow( _
       ByVal _stripComments_ As Boolean _
    ) As XElement  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim stripComments As Boolean
    Dim value As XElement
     
    value = [SpecificationFlowDefinition](topic11387.md).GetDefaultSpecificationFlow(stripComments)  
  
C#|   
---|---  
      
    
    [EditorBrowsableAttribute(EditorBrowsableState.Advanced)]
    public static XElement GetDefaultSpecificationFlow( 
       bool _stripComments_
    )  
  
#### Parameters

 _stripComments_
    True to strip comments from the specification flow XML, otherwise false.

#### Return Value

An System.Xml.Linq.XElement which has been loaded from the default specification flow definition.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[SpecificationFlowDefinition Class](topic11387.md)   
[SpecificationFlowDefinition Members](topic11388.md)


