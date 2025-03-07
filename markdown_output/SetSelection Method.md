SetSelection Method   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications Namespace](topic16.md) > [ViewControl Class](topic1119.md) : SetSelection Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_newSelection_
    The new selection.

_clone_
    Dictates whether the array is cloned, if you make any changes to the array after calling this method, you should opt to clone the array, otherwise it is safe to pass false for this parameter's argument.

Glossary Item Box

Sets the current selection. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Protected Sub SetSelection( _
       ByVal _newSelection_() As Object, _
       ByVal _clone_ As Boolean _
    )   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ViewControl](topic1119.md)
    Dim newSelection() As Object
    Dim clone As Boolean
     
    instance.SetSelection(newSelection, clone)  
  
C#|   
---|---  
      
    
    protected void SetSelection( 
       object[] _newSelection_ ,
       bool _clone_
    )  
  
#### Parameters

 _newSelection_
    The new selection.
_clone_
    Dictates whether the array is cloned, if you make any changes to the array after calling this method, you should opt to clone the array, otherwise it is safe to pass false for this parameter's argument.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ViewControl Class](topic1119.md)   
[ViewControl Members](topic1120.md)


