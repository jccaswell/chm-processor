Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
GenerationEngineException Constructor(String,Exception)   
  
[DriveWorks.SolidWorks Assembly](topic13342.md) > [DriveWorks.SolidWorks.Generation Namespace](topic15094.md) > [GenerationEngineException Class](topic15218.md) > [GenerationEngineException Constructor](topic15224.md) : GenerationEngineException Constructor(String,Exception)  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_message_
    A description of the exception.

_inner_
    The inner exception.

Glossary Item Box

Initializes an instance of the [GenerationEngineException](topic15218.md) class. 

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
     
    Dim instance As New [GenerationEngineException](topic15218.md)(message, inner)  
  
C#|   
---|---  
      
    
    public GenerationEngineException( 
       string _message_ ,
       Exception _inner_
    )  
  
#### Parameters

 _message_
    A description of the exception.
_inner_
    The inner exception.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[GenerationEngineException Class](topic15218.md)   
[GenerationEngineException Members](topic15219.md)   
[Overload List](topic15224.md)


