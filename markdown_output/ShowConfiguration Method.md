ShowConfiguration Method   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications.Extensibility Namespace](topic1995.md) > [IHasConfiguration Interface](topic2043.md) : ShowConfiguration Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_owner_
    The parent window for any dialogs.

Glossary Item Box

Shows the configuration user interface. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Sub ShowConfiguration( _
       ByVal _owner_ As IWin32Window _
    )   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [IHasConfiguration](topic2043.md)
    Dim owner As IWin32Window
     
    instance.ShowConfiguration(owner)  
  
C#|   
---|---  
      
    
    void ShowConfiguration( 
       IWin32Window _owner_
    )  
  
#### Parameters

 _owner_
    The parent window for any dialogs.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[IHasConfiguration Interface](topic2043.md)   
[IHasConfiguration Members](topic2044.md)


