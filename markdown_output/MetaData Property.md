Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
Metadata Property   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [Project Class](topic3859.md) : Metadata Property  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Gets access to the sections in the project metadata file. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    <EditorBrowsableAttribute(EditorBrowsableState.Advanced)>
    Public ReadOnly Property Metadata As [ProjectMetadata](topic4647.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [Project](topic3859.md)
    Dim value As [ProjectMetadata](topic4647.md)
     
    value = instance.Metadata  
  
C#|   
---|---  
      
    
    [EditorBrowsableAttribute(EditorBrowsableState.Advanced)]
    public [ProjectMetadata](topic4647.md) Metadata {get;}  
  
# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[Project Class](topic3859.md)   
[Project Members](topic3860.md)


