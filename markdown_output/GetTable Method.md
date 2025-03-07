Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
GetTable Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [ProjectDataTables Class](topic4311.md) : GetTable Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_name_
    The name of the table to get.

Glossary Item Box

Gets the table with the specified name. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function GetTable( _
       ByVal _name_ As String _
    ) As [ProjectDataTable](topic4282.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ProjectDataTables](topic4311.md)
    Dim name As String
    Dim value As [ProjectDataTable](topic4282.md)
     
    value = instance.GetTable(name)  
  
C#|   
---|---  
      
    
    public [ProjectDataTable](topic4282.md) GetTable( 
       string _name_
    )  
  
#### Parameters

 _name_
    The name of the table to get.

#### Return Value

The data table with the specified name.

# Exceptions

Exception| Description  
---|---  
[ItemNotFoundException](topic3571.md)| Thrown if a data table with the specified name does not exist.  
System.ArgumentNullException| Thrown if the name argument is a null reference.  
  
# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ProjectDataTables Class](topic4311.md)   
[ProjectDataTables Members](topic4312.md)


