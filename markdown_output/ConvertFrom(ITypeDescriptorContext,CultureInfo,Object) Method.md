Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
ConvertFrom(ITypeDescriptorContext,CultureInfo,Object) Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [IArrayValueConverter Class](topic3468.md) > [ConvertFrom Method](topic3479.md) : ConvertFrom(ITypeDescriptorContext,CultureInfo,Object) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_context_
    

_culture_
    

_value_
    

Glossary Item Box

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Overloads Overrides Function ConvertFrom( _
       ByVal _context_ As ITypeDescriptorContext, _
       ByVal _culture_ As CultureInfo, _
       ByVal _value_ As Object _
    ) As Object  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [IArrayValueConverter](topic3468.md)
    Dim context As ITypeDescriptorContext
    Dim culture As CultureInfo
    Dim value As Object
    Dim value As Object
     
    value = instance.ConvertFrom(context, culture, value)  
  
C#|   
---|---  
      
    
    public override object ConvertFrom( 
       ITypeDescriptorContext _context_ ,
       CultureInfo _culture_ ,
       object _value_
    )  
  
#### Parameters

 _context_
    
_culture_
    
_value_
    

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[IArrayValueConverter Class](topic3468.md)   
[IArrayValueConverter Members](topic3469.md)   
[Overload List](topic3479.md)


