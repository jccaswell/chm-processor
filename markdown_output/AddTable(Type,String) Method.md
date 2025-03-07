Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
AddTable(Type,String) Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [GroupDataTables Class](topic3136.md) > [AddTable Method](topic3142.md) : AddTable(Type,String) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_tableType_
    The type of table to create.

_name_
    The name to give the new table.

Glossary Item Box

Adds a table of the specified type to the group. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Overloads Function AddTable( _
       ByVal _tableType_ As Type, _
       ByVal _name_ As String _
    ) As [GroupDataTable](topic3110.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [GroupDataTables](topic3136.md)
    Dim tableType As Type
    Dim name As String
    Dim value As [GroupDataTable](topic3110.md)
     
    value = instance.AddTable(tableType, name)  
  
C#|   
---|---  
      
    
    public [GroupDataTable](topic3110.md) AddTable( 
       Type _tableType_ ,
       string _name_
    )  
  
#### Parameters

 _tableType_
    The type of table to create.
_name_
    The name to give the new table.

#### Return Value

The created table.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[GroupDataTables Class](topic3136.md)   
[GroupDataTables Members](topic3137.md)   
[Overload List](topic3142.md)


