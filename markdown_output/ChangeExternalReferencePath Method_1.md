Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
ChangeExternalReferencePath Method   
  
[DriveWorks.SolidWorks Assembly](topic13342.md) > [DriveWorks.SolidWorks.Components Namespace](topic13925.md) > [CapturedPart Class](topic14307.md) : ChangeExternalReferencePath Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_newPathsByOldPaths_
    Map of old paths to new paths to change in this part.

Glossary Item Box

Changes all matching alternatives in this part using the provided map. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function ChangeExternalReferencePath( _
       ByVal _newPathsByOldPaths_ As Dictionary(Of String,String) _
    ) As Boolean  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [CapturedPart](topic14307.md)
    Dim newPathsByOldPaths As Dictionary(Of String,String)
    Dim value As Boolean
     
    value = instance.ChangeExternalReferencePath(newPathsByOldPaths)  
  
C#|   
---|---  
      
    
    public bool ChangeExternalReferencePath( 
       Dictionary<string,string> _newPathsByOldPaths_
    )  
  
#### Parameters

 _newPathsByOldPaths_
    Map of old paths to new paths to change in this part.

#### Return Value

Whether or not any paths were changed.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[CapturedPart Class](topic14307.md)   
[CapturedPart Members](topic14308.md)


