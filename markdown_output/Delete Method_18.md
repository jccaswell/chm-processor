Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
Delete Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.EventFlow Namespace](topic6871.md) > [NodeOutputCollection Class](topic7087.md) : Delete Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_name_
    The name of the output to remove.

Glossary Item Box

Removes an output from the collection. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function Delete( _
       ByVal _name_ As String _
    ) As Boolean  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [NodeOutputCollection](topic7087.md)
    Dim name As String
    Dim value As Boolean
     
    value = instance.Delete(name)  
  
C#|   
---|---  
      
    
    public bool Delete( 
       string _name_
    )  
  
#### Parameters

 _name_
    The name of the output to remove.

#### Return Value

True if the output was removed, otherwise False.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[NodeOutputCollection Class](topic7087.md)   
[NodeOutputCollection Members](topic7088.md)


