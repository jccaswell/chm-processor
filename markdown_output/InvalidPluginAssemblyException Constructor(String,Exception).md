Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
InvalidPluginAssemblyException Constructor(String,Exception)   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Extensibility Namespace](topic7150.md) > [InvalidPluginAssemblyException Class](topic7191.md) > [InvalidPluginAssemblyException Constructor](topic7197.md) : InvalidPluginAssemblyException Constructor(String,Exception)  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_message_
    The message which describes the exception.

_inner_
    The inner exception.

Glossary Item Box

Initializes a new instance of the [InvalidPluginAssemblyException](topic7191.md) type. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function New( _
       ByVal _message_ As String, _
       ByVal _inner_ As Exception _
    )  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim message As String
    Dim inner As Exception
     
    Dim instance As New [InvalidPluginAssemblyException](topic7191.md)(message, inner)  
  
C#|   
---|---  
      
    
    public InvalidPluginAssemblyException( 
       string _message_ ,
       Exception _inner_
    )  
  
#### Parameters

 _message_
    The message which describes the exception.
_inner_
    The inner exception.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[InvalidPluginAssemblyException Class](topic7191.md)   
[InvalidPluginAssemblyException Members](topic7192.md)   
[Overload List](topic7197.md)


