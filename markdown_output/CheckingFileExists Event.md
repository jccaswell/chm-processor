Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
CheckingFileExists Event   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications.Autopilot.Extensibility Namespace](topic1633.md) > [IAutopilotService Interface](topic1654.md) : CheckingFileExists Event  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Raised when an Autopilot component such as a queue or connector is about to check the existence of a file. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Event CheckingFileExists As EventHandler(Of FileExistenceCheckEventArgs)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [IAutopilotService](topic1654.md)
    Dim handler As EventHandler(Of FileExistenceCheckEventArgs)
     
    AddHandler instance.CheckingFileExists, handler  
  
C#|   
---|---  
      
    
    event EventHandler<FileExistenceCheckEventArgs> CheckingFileExists  
  
# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[IAutopilotService Interface](topic1654.md)   
[IAutopilotService Members](topic1655.md)


