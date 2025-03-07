ReplaceReferenceException Constructor(String,String,String,Exception)   
  
[DriveWorks.SolidWorks Assembly](topic13342.md) > [DriveWorks.SolidWorks.Generation Namespace](topic15094.md) > [ReplaceReferenceException Class](topic15291.md) > [ReplaceReferenceException Constructor](topic15297.md) : ReplaceReferenceException Constructor(String,String,String,Exception)  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_documentPath_
    The document being rereferenced.

_masterPath_
    The original path in the document.

_targetPath_
    The new path in the document.

_inner_
    The original exception.

Glossary Item Box

Initializes a new instance of the [ReplaceReferenceException](topic15291.md)

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function New( _
       ByVal _documentPath_ As String, _
       ByVal _masterPath_ As String, _
       ByVal _targetPath_ As String, _
       ByVal _inner_ As Exception _
    )  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim documentPath As String
    Dim masterPath As String
    Dim targetPath As String
    Dim inner As Exception
     
    Dim instance As New [ReplaceReferenceException](topic15291.md)(documentPath, masterPath, targetPath, inner)  
  
C#|   
---|---  
      
    
    public ReplaceReferenceException( 
       string _documentPath_ ,
       string _masterPath_ ,
       string _targetPath_ ,
       Exception _inner_
    )  
  
#### Parameters

 _documentPath_
    The document being rereferenced.
_masterPath_
    The original path in the document.
_targetPath_
    The new path in the document.
_inner_
    The original exception.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ReplaceReferenceException Class](topic15291.md)   
[ReplaceReferenceException Members](topic15292.md)   
[Overload List](topic15297.md)


