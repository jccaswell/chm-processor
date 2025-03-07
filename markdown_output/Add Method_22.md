Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
Add Method   
  
[DriveWorks.SolidWorks Assembly](topic13342.md) > [DriveWorks.SolidWorks.Components Namespace](topic13925.md) > [ReleasedInstanceCollection Class](topic14954.md) : Add Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_address_
    The address of the instance, e.g. SomeComponent-7.

_value_
    The value of the instance parameter.

Glossary Item Box

Adds and returns a new instance. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function Add( _
       ByVal _address_ As String, _
       ByVal _value_ As String _
    ) As [ReleasedInstance](topic14946.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ReleasedInstanceCollection](topic14954.md)
    Dim address As String
    Dim value As String
    Dim value As [ReleasedInstance](topic14946.md)
     
    value = instance.Add(address, value)  
  
C#|   
---|---  
      
    
    public [ReleasedInstance](topic14946.md) Add( 
       string _address_ ,
       string _value_
    )  
  
#### Parameters

 _address_
    The address of the instance, e.g. SomeComponent-7.
_value_
    The value of the instance parameter.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ReleasedInstanceCollection Class](topic14954.md)   
[ReleasedInstanceCollection Members](topic14955.md)


