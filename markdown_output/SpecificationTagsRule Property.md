SpecificationTagsRule Property   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [ProjectSpecialVariables Class](topic4782.md) : SpecificationTagsRule Property  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Gets/sets the rule used to determine the tags associated with a specification. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public MustOverride Property SpecificationTagsRule As String  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ProjectSpecialVariables](topic4782.md)
    Dim value As String
     
    instance.SpecificationTagsRule = value
     
    value = instance.SpecificationTagsRule  
  
C#|   
---|---  
      
    
    public abstract string SpecificationTagsRule {get; set;}  
  
# Remarks

Each tag should be delimited by a pipe-bar character.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ProjectSpecialVariables Class](topic4782.md)   
[ProjectSpecialVariables Members](topic4783.md)


