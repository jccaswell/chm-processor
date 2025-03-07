Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
Add Method   
  
[DriveWorks.SolidWorks Assembly](topic13342.md) > [DriveWorks.SolidWorks.Components Namespace](topic13925.md) > [CapturedInstanceCollection Class](topic14274.md) : Add Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_address_
    The address of the instance, e.g. SomeComponent-7.

Glossary Item Box

Adds and returns a new instance. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function Add( _
       ByVal _address_ As String _
    ) As [CapturedInstance](topic14267.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [CapturedInstanceCollection](topic14274.md)
    Dim address As String
    Dim value As [CapturedInstance](topic14267.md)
     
    value = instance.Add(address)  
  
C#|   
---|---  
      
    
    public [CapturedInstance](topic14267.md) Add( 
       string _address_
    )  
  
#### Parameters

 _address_
    The address of the instance, e.g. SomeComponent-7.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[CapturedInstanceCollection Class](topic14274.md)   
[CapturedInstanceCollection Members](topic14275.md)


