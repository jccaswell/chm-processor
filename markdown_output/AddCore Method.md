Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
AddCore Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Components.Tasks Namespace](topic6391.md) > [ComponentTaskCollection Class](topic6466.md) : AddCore Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_type_
    

_name_
    

_index_
    

Glossary Item Box

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Protected MustOverride Function AddCore( _
       ByVal _type_ As Type, _
       ByVal _name_ As String, _
       ByVal _index_ As Integer _
    ) As [ComponentTask](topic6407.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ComponentTaskCollection](topic6466.md)
    Dim type As Type
    Dim name As String
    Dim index As Integer
    Dim value As [ComponentTask](topic6407.md)
     
    value = instance.AddCore(type, name, index)  
  
C#|   
---|---  
      
    
    protected abstract [ComponentTask](topic6407.md) AddCore( 
       Type _type_ ,
       string _name_ ,
       int _index_
    )  
  
#### Parameters

 _type_
    
_name_
    
_index_
    

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ComponentTaskCollection Class](topic6466.md)   
[ComponentTaskCollection Members](topic6467.md)


