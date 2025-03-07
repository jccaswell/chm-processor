Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
InvalidAttachmentsException Constructor(String[],String)   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [InvalidAttachmentsException Class](topic3504.md) > [InvalidAttachmentsException Constructor](topic3510.md) : InvalidAttachmentsException Constructor(String[],String)  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_attachments_
    The invalid attachments.

_message_
    The exception message.

Glossary Item Box

Creates a new instance of the [InvalidAttachmentsException](topic3504.md) class. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function New( _
       ByVal _attachments_() As String, _
       ByVal _message_ As String _
    )  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim attachments() As String
    Dim message As String
     
    Dim instance As New [InvalidAttachmentsException](topic3504.md)(attachments, message)  
  
C#|   
---|---  
      
    
    public InvalidAttachmentsException( 
       string[] _attachments_ ,
       string _message_
    )  
  
#### Parameters

 _attachments_
    The invalid attachments.
_message_
    The exception message.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[InvalidAttachmentsException Class](topic3504.md)   
[InvalidAttachmentsException Members](topic3505.md)   
[Overload List](topic3510.md)


