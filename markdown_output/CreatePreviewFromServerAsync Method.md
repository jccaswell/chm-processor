Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
CreatePreviewFromServerAsync Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Forms Namespace](topic7266.md) > [PreviewControl Class](topic8709.md) : CreatePreviewFromServerAsync Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Creates a preview from the server asynchronously. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    <AsyncStateMachineAttribute(DriveWorks.Forms.PreviewControl+VB$StateMachine_231_CreatePreviewFromServerAsync)>
    Public Function CreatePreviewFromServerAsync() As Task(Of PreviewServerResult)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [PreviewControl](topic8709.md)
    Dim value As Task(Of PreviewServerResult)
     
    value = instance.CreatePreviewFromServerAsync()  
  
C#|   
---|---  
      
    
    [AsyncStateMachineAttribute(DriveWorks.Forms.PreviewControl+VB$StateMachine_231_CreatePreviewFromServerAsync)]
    public Task<PreviewServerResult> CreatePreviewFromServerAsync()  
  
#### Return Value

A task that can be awaited in order to get information from the server as to the status of the preview.

# Remarks

Previewing asynchronously will allow for multiple previews over the group connection. Note: Only one preview can be active per preview control.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[PreviewControl Class](topic8709.md)   
[PreviewControl Members](topic8710.md)


