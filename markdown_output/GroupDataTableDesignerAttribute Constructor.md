Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
GroupDataTableDesignerAttribute Constructor   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications.Administrator.Extensibility.DataTables Namespace](topic1432.md) > [GroupDataTableDesignerAttribute Class](topic1488.md) : GroupDataTableDesignerAttribute Constructor  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_groupDataTableType_
    The type of group data table supported by the designer (must be derived from [DriveWorks.GroupDataTable](topic3110.md)).

_displayName_
    The localizable display name of the group data table type.

_image_
    The localizable image of the group data table type.

Glossary Item Box

Initializes a new instance of the [GroupDataTableDesignerAttribute](topic1488.md) attribute class. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function New( _
       ByVal _groupDataTableType_ As Type, _
       ByVal _displayName_ As String, _
       ByVal _image_ As String _
    )  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim groupDataTableType As Type
    Dim displayName As String
    Dim image As String
     
    Dim instance As New [GroupDataTableDesignerAttribute](topic1488.md)(groupDataTableType, displayName, image)  
  
C#|   
---|---  
      
    
    public GroupDataTableDesignerAttribute( 
       Type _groupDataTableType_ ,
       string _displayName_ ,
       string _image_
    )  
  
#### Parameters

 _groupDataTableType_
    The type of group data table supported by the designer (must be derived from [DriveWorks.GroupDataTable](topic3110.md)).
_displayName_
    The localizable display name of the group data table type.
_image_
    The localizable image of the group data table type.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[GroupDataTableDesignerAttribute Class](topic1488.md)   
[GroupDataTableDesignerAttribute Members](topic1489.md)


