Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
CopyFile(String,String) Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [ISpecificationFileCopyService Interface](topic2316.md) > [CopyFile Method](topic2325.md) : CopyFile(String,String) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_source_
    The path to the file to copy.

_target_
    The path to copy the file to.

Glossary Item Box

Copies the given file to the specified target without deleting the source file. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Overloads Sub CopyFile( _
       ByVal _source_ As String, _
       ByVal _target_ As String _
    )   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ISpecificationFileCopyService](topic2316.md)
    Dim source As String
    Dim target As String
     
    instance.CopyFile(source, target)  
  
C#|   
---|---  
      
    
    void CopyFile( 
       string _source_ ,
       string _target_
    )  
  
#### Parameters

 _source_
    The path to the file to copy.
_target_
    The path to copy the file to.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ISpecificationFileCopyService Interface](topic2316.md)   
[ISpecificationFileCopyService Members](topic2317.md)   
[Overload List](topic2325.md)


