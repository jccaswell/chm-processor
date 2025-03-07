RemoveRow Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [SqlServerExport Class](topic5417.md) : RemoveRow Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_row_
    The row to be removed.

Glossary Item Box

Removes a row from the list of rows to be exported. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Sub RemoveRow( _
       ByVal _row_ As [DataExportRowDefinition](topic2635.md) _
    )   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [SqlServerExport](topic5417.md)
    Dim row As [DataExportRowDefinition](topic2635.md)
     
    instance.RemoveRow(row)  
  
C#|   
---|---  
      
    
    public void RemoveRow( 
       [DataExportRowDefinition](topic2635.md) _row_
    )  
  
#### Parameters

 _row_
    The row to be removed.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[SqlServerExport Class](topic5417.md)   
[SqlServerExport Members](topic5418.md)


