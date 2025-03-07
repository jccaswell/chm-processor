Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
Add Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [Columns Class](topic2516.md) : Add Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_name_
    Name of the new column.

Glossary Item Box

Adds a new column to the column collection. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function Add( _
       ByVal _name_ As String _
    ) As [Column](topic2506.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [Columns](topic2516.md)
    Dim name As String
    Dim value As [Column](topic2506.md)
     
    value = instance.Add(name)  
  
C#|   
---|---  
      
    
    public [Column](topic2506.md) Add( 
       string _name_
    )  
  
#### Parameters

 _name_
    Name of the new column.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[Columns Class](topic2516.md)   
[Columns Members](topic2517.md)


