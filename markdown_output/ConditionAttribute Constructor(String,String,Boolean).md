Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
ConditionAttribute Constructor(String,String,Boolean)   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Specification Namespace](topic10764.md) > [ConditionAttribute Class](topic10832.md) > [ConditionAttribute Constructor](topic10838.md) : ConditionAttribute Constructor(String,String,Boolean)  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_displayName_
    The localized display name of the condition, or a resource string which identifies the string to use.

_image_
    A resource string which identifies the image to use.

_enableWarningOutput_
    Whether the warning output will be used.

Glossary Item Box

Initializes a new instance of the [ConditionAttribute](topic10832.md) class. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function New( _
       ByVal _displayName_ As String, _
       ByVal _image_ As String, _
       ByVal _enableWarningOutput_ As Boolean _
    )  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim displayName As String
    Dim image As String
    Dim enableWarningOutput As Boolean
     
    Dim instance As New [ConditionAttribute](topic10832.md)(displayName, image, enableWarningOutput)  
  
C#|   
---|---  
      
    
    public ConditionAttribute( 
       string _displayName_ ,
       string _image_ ,
       bool _enableWarningOutput_
    )  
  
#### Parameters

 _displayName_
    The localized display name of the condition, or a resource string which identifies the string to use.
_image_
    A resource string which identifies the image to use.
_enableWarningOutput_
    Whether the warning output will be used.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ConditionAttribute Class](topic10832.md)   
[ConditionAttribute Members](topic10833.md)   
[Overload List](topic10838.md)


