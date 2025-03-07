Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
Add Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [TableExportRow Class](topic5600.md) : Add Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_header_
    The header of the column that this cell will belong to.

Glossary Item Box

Adds a cell with the specified column header to this row. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function Add( _
       ByVal _header_ As String _
    ) As [TableExportCell](topic5560.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [TableExportRow](topic5600.md)
    Dim header As String
    Dim value As [TableExportCell](topic5560.md)
     
    value = instance.Add(header)  
  
C#|   
---|---  
      
    
    public [TableExportCell](topic5560.md) Add( 
       string _header_
    )  
  
#### Parameters

 _header_
    The header of the column that this cell will belong to.

#### Return Value

The created cell.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[TableExportRow Class](topic5600.md)   
[TableExportRow Members](topic5601.md)


