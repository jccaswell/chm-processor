Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
OdbcExport Class   
[Members](topic3764.md)   
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) : OdbcExport Class  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Provides support for exporting data to an ODBC database as part of a DriveWorks specification. 

# Object Model

![](dotnetdiagramimages/image174.png)

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Class OdbcExport 
       Inherits [ProjectDocument](topic4356.md)
       Implements [DriveWorks.Extensibility.IExtension](topic7152.md), [IDataExportDefinition](topic2177.md)   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [OdbcExport](topic3763.md)  
  
C#|   
---|---  
      
    
    public class OdbcExport : [ProjectDocument](topic4356.md), [DriveWorks.Extensibility.IExtension](topic7152.md), [IDataExportDefinition](topic2177.md)    
  
# Remarks

To create a new instance of an OdbcExport document, use the [Project](topic4395.md).[Documents](topic4434.md).[CreateDocument](topic4442.md) method.

# Inheritance Hierarchy

System.Object  
System.MarshalByRefObject  
[DriveWorks.ProjectDocument](topic4356.md)  
**DriveWorks.OdbcExport**  


# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[OdbcExport Members](topic3764.md)   
[DriveWorks Namespace](topic2159.md)


