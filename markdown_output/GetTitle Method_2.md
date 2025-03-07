Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
GetTitle Method   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications Namespace](topic16.md) > [ICommand Interface](topic77.md) : GetTitle Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_context_
    The context which would be passed to the command's invoke method.

Glossary Item Box

Gets the context-specific title of the command. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Function GetTitle( _
       ByVal _context_ As Object _
    ) As String  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ICommand](topic77.md)
    Dim context As Object
    Dim value As String
     
    value = instance.GetTitle(context)  
  
C#|   
---|---  
      
    
    string GetTitle( 
       object _context_
    )  
  
#### Parameters

 _context_
    The context which would be passed to the command's invoke method.

#### Return Value

A string containing the localized title of the command.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ICommand Interface](topic77.md)   
[ICommand Members](topic78.md)


