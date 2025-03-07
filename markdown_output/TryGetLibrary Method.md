TryGetLibrary Method   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications.Extensibility Namespace](topic1995.md) > [ILibraryManager Interface](topic2079.md) : TryGetLibrary Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_invariantName_
    The invariant name of the library to retrieve.

_result_
    Receives the specified library.

Glossary Item Box

Gets the library with the specified invariant name. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Function TryGetLibrary( _
       ByVal _invariantName_ As String, _
       ByRef _result_ As [ILibraryInfo](topic2055.md) _
    ) As Boolean  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ILibraryManager](topic2079.md)
    Dim invariantName As String
    Dim result As [ILibraryInfo](topic2055.md)
    Dim value As Boolean
     
    value = instance.TryGetLibrary(invariantName, result)  
  
C#|   
---|---  
      
    
    bool TryGetLibrary( 
       string _invariantName_ ,
       ref [ILibraryInfo](topic2055.md) _result_
    )  
  
#### Parameters

 _invariantName_
    The invariant name of the library to retrieve.
_result_
    Receives the specified library.

#### Return Value

True if the library was found and returned, otherwise false.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ILibraryManager Interface](topic2079.md)   
[ILibraryManager Members](topic2080.md)


