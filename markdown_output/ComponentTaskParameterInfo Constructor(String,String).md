Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
ComponentTaskParameterInfo Constructor(String,String)   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Components.Tasks Namespace](topic6391.md) > [ComponentTaskParameterInfo Class](topic6603.md) > [ComponentTaskParameterInfo Constructor](topic6609.md) : ComponentTaskParameterInfo Constructor(String,String)  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_name_
    The name of the parameter.

_displayName_
    The name of the parameter to show end end user.

Glossary Item Box

Creates a new instance of the [ComponentTaskParameterInfo](topic6603.md) class. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function New( _
       ByVal _name_ As String, _
       ByVal _displayName_ As String _
    )  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim name As String
    Dim displayName As String
     
    Dim instance As New [ComponentTaskParameterInfo](topic6603.md)(name, displayName)  
  
C#|   
---|---  
      
    
    public ComponentTaskParameterInfo( 
       string _name_ ,
       string _displayName_
    )  
  
#### Parameters

 _name_
    The name of the parameter.
_displayName_
    The name of the parameter to show end end user.

# Exceptions

Exception| Description  
---|---  
System.ArgumentException| name is null or empty.  
  
# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ComponentTaskParameterInfo Class](topic6603.md)   
[ComponentTaskParameterInfo Members](topic6604.md)   
[Overload List](topic6609.md)


