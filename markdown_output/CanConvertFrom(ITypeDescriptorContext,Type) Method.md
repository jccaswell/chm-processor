Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
CanConvertFrom(ITypeDescriptorContext,Type) Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [IArrayValueConverter Class](topic3468.md) > [CanConvertFrom Method](topic3475.md) : CanConvertFrom(ITypeDescriptorContext,Type) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_context_
    

_sourceType_
    

Glossary Item Box

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Overloads Overrides Function CanConvertFrom( _
       ByVal _context_ As ITypeDescriptorContext, _
       ByVal _sourceType_ As Type _
    ) As Boolean  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [IArrayValueConverter](topic3468.md)
    Dim context As ITypeDescriptorContext
    Dim sourceType As Type
    Dim value As Boolean
     
    value = instance.CanConvertFrom(context, sourceType)  
  
C#|   
---|---  
      
    
    public override bool CanConvertFrom( 
       ITypeDescriptorContext _context_ ,
       Type _sourceType_
    )  
  
#### Parameters

 _context_
    
_sourceType_
    

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[IArrayValueConverter Class](topic3468.md)   
[IArrayValueConverter Members](topic3469.md)   
[Overload List](topic3475.md)


