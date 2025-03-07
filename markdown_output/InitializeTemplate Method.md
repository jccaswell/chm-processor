Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
InitializeTemplate Method   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications.Administrator.Extensibility.Documents Namespace](topic1507.md) > [IDocumentTemplateHelper Interface](topic1526.md) : InitializeTemplate Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_application_
    The running application.

_document_
    The document to which to apply the template.

_templateData_
    The XML from the template that applies to this document

_replacements_
    A collection of names and their replacements that should be applied when adding rules to the document.

Glossary Item Box

Applies the settings from the given template to the given document. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Sub InitializeTemplate( _
       ByVal _application_ As [IApplication](topic24.md), _
       ByVal _document_ As [ProjectDocument](topic4356.md), _
       ByVal _templateData_ As XElement, _
       ByVal _replacements_ As Dictionary(Of String,String) _
    )   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [IDocumentTemplateHelper](topic1526.md)
    Dim application As [IApplication](topic24.md)
    Dim document As [ProjectDocument](topic4356.md)
    Dim templateData As XElement
    Dim replacements As Dictionary(Of String,String)
     
    instance.InitializeTemplate(application, document, templateData, replacements)  
  
C#|   
---|---  
      
    
    void InitializeTemplate( 
       [IApplication](topic24.md) _application_ ,
       [ProjectDocument](topic4356.md) _document_ ,
       XElement _templateData_ ,
       Dictionary<string,string> _replacements_
    )  
  
#### Parameters

 _application_
    The running application.
_document_
    The document to which to apply the template.
_templateData_
    The XML from the template that applies to this document
 _replacements_
    A collection of names and their replacements that should be applied when adding rules to the document.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[IDocumentTemplateHelper Interface](topic1526.md)   
[IDocumentTemplateHelper Members](topic1527.md)


