RemoteGroupServer Constructor   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [RemoteGroupServer Class](topic5192.md) : RemoteGroupServer Constructor  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_connectionString_
    The connection string to use to connect to the SQL Server.

Glossary Item Box

Creates a new remote group server for the specified SQL Server connection. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function New( _
       ByVal _connectionString_ As String _
    )  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim connectionString As String
     
    Dim instance As New [RemoteGroupServer](topic5192.md)(connectionString)  
  
C#|   
---|---  
      
    
    public RemoteGroupServer( 
       string _connectionString_
    )  
  
#### Parameters

 _connectionString_
    The connection string to use to connect to the SQL Server.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[RemoteGroupServer Class](topic5192.md)   
[RemoteGroupServer Members](topic5193.md)


