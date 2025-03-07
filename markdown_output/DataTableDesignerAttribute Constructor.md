Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
DataTableDesignerAttribute Constructor   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications.Administrator.Extensibility.DataTables Namespace](topic1432.md) > [DataTableDesignerAttribute Class](topic1478.md) : DataTableDesignerAttribute Constructor  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_dataTableType_
    The type of data table supported by the designer (must be derived from [DriveWorks.ProjectDataTable](topic4282.md)).

_displayName_
    The localizable display name of the data table type.

_image_
    The localizable image of the data table type.

Glossary Item Box

Initializes a new instance of the [DataTableDesignerAttribute](topic1478.md) attribute class. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function New( _
       ByVal _dataTableType_ As Type, _
       ByVal _displayName_ As String, _
       ByVal _image_ As String _
    )  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim dataTableType As Type
    Dim displayName As String
    Dim image As String
     
    Dim instance As New [DataTableDesignerAttribute](topic1478.md)(dataTableType, displayName, image)  
  
C#|   
---|---  
      
    
    public DataTableDesignerAttribute( 
       Type _dataTableType_ ,
       string _displayName_ ,
       string _image_
    )  
  
#### Parameters

 _dataTableType_
    The type of data table supported by the designer (must be derived from [DriveWorks.ProjectDataTable](topic4282.md)).
_displayName_
    The localizable display name of the data table type.
_image_
    The localizable image of the data table type.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[DataTableDesignerAttribute Class](topic1478.md)   
[DataTableDesignerAttribute Members](topic1479.md)


