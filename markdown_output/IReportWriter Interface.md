Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
IReportWriter Interface   
[Members](topic10345.md)   
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Reporting Namespace](topic10334.md) : IReportWriter Interface  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Provides a contract for report writers capable of logging reports for the DriveWorks Engine. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Interface IReportWriter   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [IReportWriter](topic10344.md)  
  
C#|   
---|---  
      
    
    public interface IReportWriter   
  
# Remarks

This interface is not intended to be implemented by 3rd party code as it may change from one release of DriveWorks to another. To implement a report writer, inherit from [ReportWriterBase](topic10476.md) or a derived class.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[IReportWriter Members](topic10345.md)   
[DriveWorks.Reporting Namespace](topic10334.md)


