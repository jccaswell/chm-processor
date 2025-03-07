Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
GetComponents(Boolean) Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [GroupCapturedComponents Class](topic3022.md) > [GetComponents Method](topic3039.md) : GetComponents(Boolean) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_includeDeletedComponents_
    True to include components which have been deleted in the results.

Glossary Item Box

Gets information about all of the captured components in the group. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Overloads Function GetComponents( _
       ByVal _includeDeletedComponents_ As Boolean _
    ) As [CapturedComponentInfo()](topic6154.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [GroupCapturedComponents](topic3022.md)
    Dim includeDeletedComponents As Boolean
    Dim value() As [CapturedComponentInfo](topic6154.md)
     
    value = instance.GetComponents(includeDeletedComponents)  
  
C#|   
---|---  
      
    
    public [CapturedComponentInfo[]](topic6154.md) GetComponents( 
       bool _includeDeletedComponents_
    )  
  
#### Parameters

 _includeDeletedComponents_
    True to include components which have been deleted in the results.

#### Return Value

An array containing one instance of the [DriveWorks.Components.CapturedComponentInfo](topic6154.md) class for each captured component.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[GroupCapturedComponents Class](topic3022.md)   
[GroupCapturedComponents Members](topic3023.md)   
[Overload List](topic3039.md)


