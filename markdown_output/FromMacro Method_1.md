Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
FromMacro Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Transactions Namespace](topic12835.md) > [NodeCollectionRef Class](topic12900.md) : FromMacro Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_specificationMacro_
    The macro for which to get a reference.

Glossary Item Box

Gets a node collection ref from a macro. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Shared Function FromMacro( _
       ByVal _specificationMacro_ As [SpecificationMacro](topic11429.md) _
    ) As [NodeCollectionRef](topic12900.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim specificationMacro As [SpecificationMacro](topic11429.md)
    Dim value As [NodeCollectionRef](topic12900.md)
     
    value = [NodeCollectionRef](topic12900.md).FromMacro(specificationMacro)  
  
C#|   
---|---  
      
    
    public static [NodeCollectionRef](topic12900.md) FromMacro( 
       [SpecificationMacro](topic11429.md) _specificationMacro_
    )  
  
#### Parameters

 _specificationMacro_
    The macro for which to get a reference.

#### Return Value

A reference to the node collection represented by the given macro.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[NodeCollectionRef Class](topic12900.md)   
[NodeCollectionRef Members](topic12901.md)


