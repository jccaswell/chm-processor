Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
GetTypeFromLibrary Method   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications.Extensibility Namespace](topic1995.md) > [ILibraryManager Interface](topic2079.md) : GetTypeFromLibrary Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_fullTypeName_
    The type string which identifies the name of the type and its parent library.

_throwOnError_
    True to throw an error if the type cannot be found, false to return a null reference (Nothing in Visual Basic).

Glossary Item Box

Gets a type from a library. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Function GetTypeFromLibrary( _
       ByVal _fullTypeName_ As String, _
       ByVal _throwOnError_ As Boolean _
    ) As Type  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ILibraryManager](topic2079.md)
    Dim fullTypeName As String
    Dim throwOnError As Boolean
    Dim value As Type
     
    value = instance.GetTypeFromLibrary(fullTypeName, throwOnError)  
  
C#|   
---|---  
      
    
    Type GetTypeFromLibrary( 
       string _fullTypeName_ ,
       bool _throwOnError_
    )  
  
#### Parameters

 _fullTypeName_
    The type string which identifies the name of the type and its parent library.
_throwOnError_
    True to throw an error if the type cannot be found, false to return a null reference (Nothing in Visual Basic).

#### Return Value

The specified type.

# Exceptions

Exception| Description  
---|---  
[DriveWorks.ItemNotFoundException](topic3571.md)| The specified type could not be found.  
  
# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ILibraryManager Interface](topic2079.md)   
[ILibraryManager Members](topic2080.md)


