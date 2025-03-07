Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
Add Method   
  
[DriveWorks.SolidWorks Assembly](topic13342.md) > [DriveWorks.SolidWorks.Components Namespace](topic13925.md) > [CapturedViewCollection Class](topic14362.md) : Add Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_sheetName_
    

_name_
    

Glossary Item Box

Adds a new view. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function Add( _
       ByVal _sheetName_ As String, _
       ByVal _name_ As String _
    ) As [CapturedView](topic14351.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [CapturedViewCollection](topic14362.md)
    Dim sheetName As String
    Dim name As String
    Dim value As [CapturedView](topic14351.md)
     
    value = instance.Add(sheetName, name)  
  
C#|   
---|---  
      
    
    public [CapturedView](topic14351.md) Add( 
       string _sheetName_ ,
       string _name_
    )  
  
#### Parameters

 _sheetName_
    
_name_
    

#### Return Value

The newly created view.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[CapturedViewCollection Class](topic14362.md)   
[CapturedViewCollection Members](topic14363.md)


