RequiresName Property   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications.Extensibility Namespace](topic1995.md) > [IProjectTemplateHelper Interface](topic2091.md) : RequiresName Property  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Determines whether the template requires a name. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    ReadOnly Property RequiresName As Boolean  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [IProjectTemplateHelper](topic2091.md)
    Dim value As Boolean
     
    value = instance.RequiresName  
  
C#|   
---|---  
      
    
    bool RequiresName {get;}  
  
# Exceptions

Exception| Description  
---|---  
System.InvalidOperationException| The template helper has not been initialized.  
  
# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[IProjectTemplateHelper Interface](topic2091.md)   
[IProjectTemplateHelper Members](topic2092.md)


