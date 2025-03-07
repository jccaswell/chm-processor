Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
Close Method   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications.Administrator.Extensibility.DataTables Namespace](topic1432.md) > [IGroupDataTableViewController Interface](topic1471.md) : Close Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Called by the data table management view to notify the data table view UI that it is being closed by the user. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Function Close() As Boolean  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [IGroupDataTableViewController](topic1471.md)
    Dim value As Boolean
     
    value = instance.Close()  
  
C#|   
---|---  
      
    
    bool Close()  
  
#### Return Value

False to abort closing the view, otherwise true. Please note that no message will be shown to the user if the close is aborted, therefore it is up to the view to let the user know why the close was aborted.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[IGroupDataTableViewController Interface](topic1471.md)   
[IGroupDataTableViewController Members](topic1472.md)


