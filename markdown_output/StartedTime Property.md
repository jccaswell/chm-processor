StartedTime Property   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [Job Class](topic3582.md) : StartedTime Property  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Gets the last time this job was attempted or nothing if no attempts have been made to process it. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public ReadOnly Property StartedTime As Nullable(Of Date)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [Job](topic3582.md)
    Dim value As Nullable(Of Date)
     
    value = instance.StartedTime  
  
C#|   
---|---  
      
    
    public Nullable<DateTime> StartedTime {get;}  
  
# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[Job Class](topic3582.md)   
[Job Members](topic3583.md)


