Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
FileSavePostNotify Event   
  
[DriveWorks.SolidWorks Assembly](topic13342.md) > [DriveWorks.SolidWorks Namespace](topic13345.md) > [ISolidWorksState Interface](topic13419.md) : FileSavePostNotify Event  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Post-notifies the user program when a file is saved in SolidWorks. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Event FileSavePostNotify As EventHandler(Of FileSavePostNotifyEventArgs)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ISolidWorksState](topic13419.md)
    Dim handler As EventHandler(Of FileSavePostNotifyEventArgs)
     
    AddHandler instance.FileSavePostNotify, handler  
  
C#|   
---|---  
      
    
    event EventHandler<FileSavePostNotifyEventArgs> FileSavePostNotify  
  
# Event Data

The event handler receives an argument of type [FileSavePostNotifyEventArgs](topic13661.md) containing data related to this event. The following **FileSavePostNotifyEventArgs** properties provide information specific to this event.

Property| Description  
---|---  
[FileName](topic13668.md)| Gets the name of the file that was saved.   
[SaveType](topic13669.md)| Gets the type of save as defined in swFileSaveTypes_e.   
[Success](topic13916.md)| Gets/sets the result of the event (default is True). (Inherited from [DriveWorks.SolidWorks.ResultEventArgs](topic13909.md))  
  
# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ISolidWorksState Interface](topic13419.md)   
[ISolidWorksState Members](topic13420.md)


