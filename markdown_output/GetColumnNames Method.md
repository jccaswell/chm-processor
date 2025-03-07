Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
GetColumnNames Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [RollupDataTable Class](topic5240.md) : GetColumnNames Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_includeDefault_
    If True, includes the default columns in the result. By default this is False.

Glossary Item Box

Gets the names of the columns that data will be retrieved for in any child specifications. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function GetColumnNames( _
       Optional ByVal _includeDefault_ As Boolean _
    ) As String()  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [RollupDataTable](topic5240.md)
    Dim includeDefault As Boolean
    Dim value() As String
     
    value = instance.GetColumnNames(includeDefault)  
  
C#|   
---|---  
      
    
    public string[] GetColumnNames( 
       bool _includeDefault_
    )  
  
#### Parameters

 _includeDefault_
    If True, includes the default columns in the result. By default this is False.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[RollupDataTable Class](topic5240.md)   
[RollupDataTable Members](topic5241.md)


