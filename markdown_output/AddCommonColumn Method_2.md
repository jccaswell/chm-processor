Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
AddCommonColumn Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [SqlServerExport Class](topic5417.md) : AddCommonColumn Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_name_
    The name of this column.

_type_
    The data type for this column.

_commonRule_
    The common rule to set for this column.

_commonComment_
    The common comment to set for the column.

Glossary Item Box

Adds a common column to the table. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function AddCommonColumn( _
       ByVal _name_ As String, _
       ByVal _type_ As String, _
       ByVal _commonRule_ As String, _
       ByVal _commonComment_ As String _
    ) As DataExportColumnDefinition  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [SqlServerExport](topic5417.md)
    Dim name As String
    Dim type As String
    Dim commonRule As String
    Dim commonComment As String
    Dim value As DataExportColumnDefinition
     
    value = instance.AddCommonColumn(name, type, commonRule, commonComment)  
  
C#|   
---|---  
      
    
    public DataExportColumnDefinition AddCommonColumn( 
       string _name_ ,
       string _type_ ,
       string _commonRule_ ,
       string _commonComment_
    )  
  
#### Parameters

 _name_
    The name of this column.
_type_
    The data type for this column.
_commonRule_
    The common rule to set for this column.
_commonComment_
    The common comment to set for the column.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[SqlServerExport Class](topic5417.md)   
[SqlServerExport Members](topic5418.md)


