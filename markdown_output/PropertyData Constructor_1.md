Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
PropertyData Constructor   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Forms.DataModel.Serialization Namespace](topic9591.md) > [PropertyData Class](topic9611.md) : PropertyData Constructor  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_name_
    The name of the property.

_dp_
    The instance of the property.

Glossary Item Box

Initializes a new instance of the [PropertyData](topic9611.md) type. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function New( _
       ByVal _name_ As String, _
       ByVal _dp_ As [DynamicProperty](topic9398.md) _
    )  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim name As String
    Dim dp As [DynamicProperty](topic9398.md)
     
    Dim instance As New [PropertyData](topic9611.md)(name, dp)  
  
C#|   
---|---  
      
    
    public PropertyData( 
       string _name_ ,
       [DynamicProperty](topic9398.md) _dp_
    )  
  
#### Parameters

 _name_
    The name of the property.
_dp_
    The instance of the property.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[PropertyData Class](topic9611.md)   
[PropertyData Members](topic9612.md)


