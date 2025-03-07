Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
Add Method   
  
[DriveWorks.SolidWorks Assembly](topic13342.md) > [DriveWorks.SolidWorks.Components Namespace](topic13925.md) > [CapturedAnnotationCollection Class](topic14063.md) : Add Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_name_
    

_address_
    

_type_
    

Glossary Item Box

Adds a new annotation. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function Add( _
       ByVal _name_ As String, _
       ByVal _address_ As String, _
       ByVal _type_ As SolidWorks.Interop.swconst.swAnnotationType_e _
    ) As [CapturedAnnotation](topic14054.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [CapturedAnnotationCollection](topic14063.md)
    Dim name As String
    Dim address As String
    Dim type As SolidWorks.Interop.swconst.swAnnotationType_e
    Dim value As [CapturedAnnotation](topic14054.md)
     
    value = instance.Add(name, address, type)  
  
C#|   
---|---  
      
    
    public [CapturedAnnotation](topic14054.md) Add( 
       string _name_ ,
       string _address_ ,
       SolidWorks.Interop.swconst.swAnnotationType_e _type_
    )  
  
#### Parameters

 _name_
    
_address_
    
_type_
    

#### Return Value

The newly created annotation.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[CapturedAnnotationCollection Class](topic14063.md)   
[CapturedAnnotationCollection Members](topic14064.md)


