Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
FileFormatGenerator.AdditionalFileGeneratedEventHandler Delegate   
  
[DriveWorks.SolidWorks Assembly](topic13342.md) > [DriveWorks.SolidWorks Namespace](topic13345.md) : FileFormatGenerator.AdditionalFileGeneratedEventHandler Delegate  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_sender_
    

_e_
    

Glossary Item Box

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Delegate Sub FileFormatGenerator.AdditionalFileGeneratedEventHandler( _
       ByVal _sender_ As Object, _
       ByVal _e_ As [FileFormatGenerationEventArgs](topic15202.md) _
    )   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As New [FileFormatGenerator.AdditionalFileGeneratedEventHandler](topic13924.md)(AddressOf HandlerMethod)  
  
C#|   
---|---  
      
    
    public delegate void FileFormatGenerator.AdditionalFileGeneratedEventHandler( 
       object _sender_ ,
       [FileFormatGenerationEventArgs](topic15202.md) _e_
    )  
  
#### Parameters

 _sender_
    
_e_
    

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[FileFormatGenerator.AdditionalFileGeneratedEventHandler Members](topic13924.md)   
[DriveWorks.SolidWorks Namespace](topic13345.md)


