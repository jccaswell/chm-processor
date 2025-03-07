SetCompleted Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [JobQueue Class](topic3594.md) : SetCompleted Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_jobId_
    The Id of the job that was completed.

Glossary Item Box

Flags the specified job as having been completed by the current client. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Sub SetCompleted( _
       ByVal _jobId_ As String _
    )   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [JobQueue](topic3594.md)
    Dim jobId As String
     
    instance.SetCompleted(jobId)  
  
C#|   
---|---  
      
    
    public void SetCompleted( 
       string _jobId_
    )  
  
#### Parameters

 _jobId_
    The Id of the job that was completed.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[JobQueue Class](topic3594.md)   
[JobQueue Members](topic3595.md)


