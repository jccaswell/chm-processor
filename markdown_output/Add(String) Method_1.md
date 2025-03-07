Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
Add(String) Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [ProjectCalculationTables Class](topic4000.md) > [Add Method](topic4006.md) : Add(String) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_displayName_
    The name of the table to create.

Glossary Item Box

Creates a new table in this collection. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Overloads Function Add( _
       ByVal _displayName_ As String _
    ) As [ProjectCalculationTable](topic3926.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ProjectCalculationTables](topic4000.md)
    Dim displayName As String
    Dim value As [ProjectCalculationTable](topic3926.md)
     
    value = instance.Add(displayName)  
  
C#|   
---|---  
      
    
    public [ProjectCalculationTable](topic3926.md) Add( 
       string _displayName_
    )  
  
#### Parameters

 _displayName_
    The name of the table to create.

#### Return Value

The created table.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ProjectCalculationTables Class](topic4000.md)   
[ProjectCalculationTables Members](topic4001.md)   
[Overload List](topic4006.md)


