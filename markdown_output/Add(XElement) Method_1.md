Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
Add(XElement) Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [ProjectCalculationTables Class](topic4000.md) > [Add Method](topic4006.md) : Add(XElement) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_tableElement_
    The System.Xml.Linq.XElement representing a Calculation Table.

Glossary Item Box

Creates a new table in this collection from the provided System.Xml.Linq.XElement. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Overloads Function Add( _
       ByVal _tableElement_ As XElement _
    ) As [ProjectCalculationTable](topic3926.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ProjectCalculationTables](topic4000.md)
    Dim tableElement As XElement
    Dim value As [ProjectCalculationTable](topic3926.md)
     
    value = instance.Add(tableElement)  
  
C#|   
---|---  
      
    
    public [ProjectCalculationTable](topic3926.md) Add( 
       XElement _tableElement_
    )  
  
#### Parameters

 _tableElement_
    The System.Xml.Linq.XElement representing a Calculation Table.

#### Return Value

The newly created [ProjectCalculationTable](topic3926.md).

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ProjectCalculationTables Class](topic4000.md)   
[ProjectCalculationTables Members](topic4001.md)   
[Overload List](topic4006.md)


