Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
CreateCondition(String,String) Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.EventFlow Namespace](topic6871.md) > [NodeOutputCollection Class](topic7087.md) > [CreateCondition Method](topic7097.md) : CreateCondition(String,String) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_name_
    The user-friendly name of the condition.

_description_
    The user-friendly description of the condition.

Glossary Item Box

Adds a condition output to the collection. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Overloads Function CreateCondition( _
       ByVal _name_ As String, _
       ByVal _description_ As String _
    ) As [ConditionOutput](topic6901.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [NodeOutputCollection](topic7087.md)
    Dim name As String
    Dim description As String
    Dim value As [ConditionOutput](topic6901.md)
     
    value = instance.CreateCondition(name, description)  
  
C#|   
---|---  
      
    
    public [ConditionOutput](topic6901.md) CreateCondition( 
       string _name_ ,
       string _description_
    )  
  
#### Parameters

 _name_
    The user-friendly name of the condition.
_description_
    The user-friendly description of the condition.

#### Return Value

The newly created condition output.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[NodeOutputCollection Class](topic7087.md)   
[NodeOutputCollection Members](topic7088.md)   
[Overload List](topic7097.md)


