Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
ConvertToNativeType Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Specification Namespace](topic10764.md) > [FlowProperty<T> Class](topic10978.md) : ConvertToNativeType Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_obj_
    

Glossary Item Box

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Overrides Function ConvertToNativeType( _
       ByVal _obj_ As Object _
    ) As Object  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [FlowProperty(Of T)](topic10978.md)
    Dim obj As Object
    Dim value As Object
     
    value = instance.ConvertToNativeType(obj)  
  
C#|   
---|---  
      
    
    public override object ConvertToNativeType( 
       object _obj_
    )  
  
#### Parameters

 _obj_
    

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[FlowProperty<T> Class](topic10978.md)   
[FlowProperty<T> Members](topic10979.md)


