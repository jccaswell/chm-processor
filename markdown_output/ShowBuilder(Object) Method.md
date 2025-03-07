ShowBuilder(Object) Method   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications.Administrator.Extensibility.RulesBuilder Namespace](topic1581.md) > [IRulesBuilderService Interface](topic1598.md) > [ShowBuilder Method](topic1604.md) : ShowBuilder(Object) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_context_
    The rules aware object, for example, a [DriveWorks.ProjectVariable](topic4927.md), an object implementing [DriveWorks.Abstractions.IHasRule](topic5947.md), or an array of such objects.

Glossary Item Box

Shows the rules builder for the given rules-aware object. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Overloads Function ShowBuilder( _
       ByVal _context_ As Object _
    ) As [RulesBuilderResult](topic1622.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [IRulesBuilderService](topic1598.md)
    Dim context As Object
    Dim value As [RulesBuilderResult](topic1622.md)
     
    value = instance.ShowBuilder(context)  
  
C#|   
---|---  
      
    
    [RulesBuilderResult](topic1622.md) ShowBuilder( 
       object _context_
    )  
  
#### Parameters

 _context_
    The rules aware object, for example, a [DriveWorks.ProjectVariable](topic4927.md), an object implementing [DriveWorks.Abstractions.IHasRule](topic5947.md), or an array of such objects.

#### Return Value

A result object.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[IRulesBuilderService Interface](topic1598.md)   
[IRulesBuilderService Members](topic1599.md)   
[Overload List](topic1604.md)


