Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
Evaluate Method   
  
[DriveWorks.SolidWorks Assembly](topic13342.md) > [DriveWorks.SolidWorks Namespace](topic13345.md) > [DimensionValueCondition Class](topic13536.md) : Evaluate Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_model_
    

_component_
    

_generationSettings_
    

Glossary Item Box

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Protected Overrides Function Evaluate( _
       ByVal _model_ As SldWorksModelProxy, _
       ByVal _component_ As [ReleasedComponent](topic6324.md), _
       ByVal _generationSettings_ As [GenerationSettings](topic15238.md) _
    ) As Boolean  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [DimensionValueCondition](topic13536.md)
    Dim model As SldWorksModelProxy
    Dim component As [ReleasedComponent](topic6324.md)
    Dim generationSettings As [GenerationSettings](topic15238.md)
    Dim value As Boolean
     
    value = instance.Evaluate(model, component, generationSettings)  
  
C#|   
---|---  
      
    
    protected override bool Evaluate( 
       SldWorksModelProxy _model_ ,
       [ReleasedComponent](topic6324.md) _component_ ,
       [GenerationSettings](topic15238.md) _generationSettings_
    )  
  
#### Parameters

 _model_
    
_component_
    
_generationSettings_
    

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[DimensionValueCondition Class](topic13536.md)   
[DimensionValueCondition Members](topic13537.md)


