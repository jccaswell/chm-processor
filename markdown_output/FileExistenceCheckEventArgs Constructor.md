Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
FileExistenceCheckEventArgs Constructor   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications.Autopilot.Extensibility Namespace](topic1633.md) > [FileExistenceCheckEventArgs Class](topic1849.md) : FileExistenceCheckEventArgs Constructor  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_filePath_
    The file path of the file that is having its existence checked.

Glossary Item Box

Creates a new [FileExistenceCheckEventArgs](topic1849.md). 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function New( _
       ByVal _filePath_ As String _
    )  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim filePath As String
     
    Dim instance As New [FileExistenceCheckEventArgs](topic1849.md)(filePath)  
  
C#|   
---|---  
      
    
    public FileExistenceCheckEventArgs( 
       string _filePath_
    )  
  
#### Parameters

 _filePath_
    The file path of the file that is having its existence checked.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[FileExistenceCheckEventArgs Class](topic1849.md)   
[FileExistenceCheckEventArgs Members](topic1850.md)


