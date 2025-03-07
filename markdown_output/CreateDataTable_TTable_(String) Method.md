_TTable_
    The type of the table to add.

Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
CreateDataTable<TTable>(String) Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [ProjectDataTables Class](topic4311.md) > [CreateDataTable Method](topic4317.md) : CreateDataTable<TTable>(String) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_name_
    The name of the table to add.

Glossary Item Box

Creates and adds a new document to the project. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Overloads Function CreateDataTable(Of TTable As [ProjectDataTable](topic4282.md))( _
       ByVal _name_ As String _
    ) As [ProjectDataTable](topic4282.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ProjectDataTables](topic4311.md)
    Dim name As String
    Dim value As [ProjectDataTable](topic4282.md)
     
    value = instance.CreateDataTable(Of TTable)(name)  
  
C#|   
---|---  
      
    
    public [ProjectDataTable](topic4282.md) CreateDataTable<TTable>( 
       string _name_
    )
    where TTable: [ProjectDataTable](topic4282.md)  
  
#### Parameters

 _name_
    The name of the table to add.

#### Type Parameters

_TTable_
    The type of the table to add.

#### Return Value

The newly created table.

# Exceptions

Exception| Description  
---|---  
[ItemExistsException](topic3561.md)| A table with the given name already exists.  
System.ArgumentOutOfRangeException| The specified type does not inherit from [ProjectDataTable](topic4282.md).  
  
# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ProjectDataTables Class](topic4311.md)   
[ProjectDataTables Members](topic4312.md)   
[Overload List](topic4317.md)


