Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
FailedTime Property   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [Job Class](topic3582.md) : FailedTime Property  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Gets the last time we received a failure notification for this job from the client or nothing if no attempts have been made to process the job yet. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public ReadOnly Property FailedTime As Nullable(Of Date)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [Job](topic3582.md)
    Dim value As Nullable(Of Date)
     
    value = instance.FailedTime  
  
C#|   
---|---  
      
    
    public Nullable<DateTime> FailedTime {get;}  
  
# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[Job Class](topic3582.md)   
[Job Members](topic3583.md)


