Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
CopyingMasterModel Event   
  
[DriveWorks.SolidWorks Assembly](topic13342.md) > [DriveWorks.SolidWorks.Generation Namespace](topic15094.md) > [IDrawingGenerationContext Interface](topic15135.md) : CopyingMasterModel Event  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Raised when the drawing is about to get copied to the target location. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Event CopyingMasterModel As EventHandler(Of FileCopyingEventArgs)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [IDrawingGenerationContext](topic15135.md)
    Dim handler As EventHandler(Of FileCopyingEventArgs)
     
    AddHandler instance.CopyingMasterModel, handler  
  
C#|   
---|---  
      
    
    event EventHandler<FileCopyingEventArgs> CopyingMasterModel  
  
# Event Data

The event handler receives an argument of type [FileCopyingEventArgs](topic2859.md) containing data related to this event. The following **FileCopyingEventArgs** properties provide information specific to this event.

Property| Description  
---|---  
[FileCopied](topic2866.md)| Gets/sets whether the file has been copied or not.   
[OverWrite](topic2867.md)| Gets whether the target file should be overwritten if it exists.   
[SourcePath](topic2868.md)| Gets the path to the source file that should be copied.   
[TargetPath](topic2869.md)| Gets the path the source file should be copied to.   
  
# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[IDrawingGenerationContext Interface](topic15135.md)   
[IDrawingGenerationContext Members](topic15136.md)


