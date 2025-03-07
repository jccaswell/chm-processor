Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
GenerateCore Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [ProjectDocument Class](topic4356.md) : GenerateCore Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_generateDirectory_
    The full path to the directory which generated files' paths should be created relative to.

_results_
    The calculated rule results for the document.

Glossary Item Box

When overridden in a derived class, generates the document. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Protected MustOverride Sub GenerateCore( _
       ByVal _generateDirectory_ As String, _
       ByVal _results_ As [RuleResults](topic11136.md) _
    )   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ProjectDocument](topic4356.md)
    Dim generateDirectory As String
    Dim results As [RuleResults](topic11136.md)
     
    instance.GenerateCore(generateDirectory, results)  
  
C#|   
---|---  
      
    
    protected abstract void GenerateCore( 
       string _generateDirectory_ ,
       [RuleResults](topic11136.md) _results_
    )  
  
#### Parameters

 _generateDirectory_
    The full path to the directory which generated files' paths should be created relative to.
_results_
    The calculated rule results for the document.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ProjectDocument Class](topic4356.md)   
[ProjectDocument Members](topic4357.md)


