Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
OnPriorityOnlyProcessingChanged Method   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications.Autopilot.Extensibility Namespace](topic1633.md) > [IAutopilotService Interface](topic1654.md) : OnPriorityOnlyProcessingChanged Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_value_
    

Glossary Item Box

Raises the [PriorityOnlyProcessingChanged](topic1684.md) event with the provided value. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Sub OnPriorityOnlyProcessingChanged( _
       ByVal _value_ As Boolean _
    )   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [IAutopilotService](topic1654.md)
    Dim value As Boolean
     
    instance.OnPriorityOnlyProcessingChanged(value)  
  
C#|   
---|---  
      
    
    void OnPriorityOnlyProcessingChanged( 
       bool _value_
    )  
  
#### Parameters

 _value_
    

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[IAutopilotService Interface](topic1654.md)   
[IAutopilotService Members](topic1655.md)


