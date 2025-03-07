Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
DeleteFeatureGenerationTask Class   
[Members](topic15310.md)   
[DriveWorks.SolidWorks Assembly](topic13342.md) > [DriveWorks.SolidWorks.Generation.Extensibility.GenerationTasks.Tasks Namespace](topic15301.md) : DeleteFeatureGenerationTask Class  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

# Object Model

![](dotnetdiagramimages/image874.png)

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    <[GenerationTaskAttribute](topic13693.md)(Scope=GenerationTaskScope.Assemblies Or  _
        GenerationTaskScope.Parts, 
       Name="resx://DriveWorks.SolidWorks.TasksLocalizedResources,DeleteFeatureTaskTitle", 
       Description="resx://DriveWorks.SolidWorks.TasksLocalizedResources,DeleteFeatureTaskDescription", 
       Image="embedded://DriveWorks.SolidWorks.DeleteFeaturePlain16.png", 
       Category="resx://DriveWorks.SolidWorks.TasksLocalizedResources,TaskCategoryPartsAndAssemblies", 
       AllowedLocations=ComponentTaskSequenceLocation.Before Or  _
        ComponentTaskSequenceLocation.After)>
    Public Class DeleteFeatureGenerationTask 
       Inherits [DriveWorks.SolidWorks.GenerationTask](topic13678.md)
       Implements [DriveWorks.Components.Tasks.IComponentTask](topic6393.md), [DriveWorks.Extensibility.IExtension](topic7152.md)   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [DeleteFeatureGenerationTask](topic15309.md)  
  
C#|   
---|---  
      
    
    [[GenerationTaskAttribute](topic13693.md)(Scope=GenerationTaskScope.Assemblies | 
        GenerationTaskScope.Parts, 
       Name="resx://DriveWorks.SolidWorks.TasksLocalizedResources,DeleteFeatureTaskTitle", 
       Description="resx://DriveWorks.SolidWorks.TasksLocalizedResources,DeleteFeatureTaskDescription", 
       Image="embedded://DriveWorks.SolidWorks.DeleteFeaturePlain16.png", 
       Category="resx://DriveWorks.SolidWorks.TasksLocalizedResources,TaskCategoryPartsAndAssemblies", 
       AllowedLocations=ComponentTaskSequenceLocation.Before | 
        ComponentTaskSequenceLocation.After)]
    public class DeleteFeatureGenerationTask : [DriveWorks.SolidWorks.GenerationTask](topic13678.md), [DriveWorks.Components.Tasks.IComponentTask](topic6393.md), [DriveWorks.Extensibility.IExtension](topic7152.md)    
  
# Inheritance Hierarchy

System.Object  
[DriveWorks.SolidWorks.GenerationTask](topic13678.md)  
**DriveWorks.SolidWorks.Generation.Extensibility.GenerationTasks.Tasks.DeleteFeatureGenerationTask**  


# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[DeleteFeatureGenerationTask Members](topic15310.md)   
[DriveWorks.SolidWorks.Generation.Extensibility.GenerationTasks.Tasks Namespace](topic15301.md)


