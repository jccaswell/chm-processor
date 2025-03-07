Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
ChildId Property   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Components Namespace](topic6089.md) > [ReleasedComponentReferenceDetails Class](topic6356.md) : ChildId Property  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

The unique id of the child driven component to which the reference applies, if appropriate. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    <DebuggerDisplayAttribute(Value="Guid = {DebugGetChildIdAsString()", 
       Name="", 
       Type="", 
       Target=, 
       TargetTypeName="")>
    Public Property ChildId As Nullable(Of Guid)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ReleasedComponentReferenceDetails](topic6356.md)
    Dim value As Nullable(Of Guid)
     
    instance.ChildId = value
     
    value = instance.ChildId  
  
C#|   
---|---  
      
    
    [DebuggerDisplayAttribute(Value="Guid = {DebugGetChildIdAsString()", 
       Name="", 
       Type="", 
       Target=, 
       TargetTypeName="")]
    public Nullable<Guid> ChildId {get; set;}  
  
# Remarks

This value is only specified if the reference is to a driven component.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ReleasedComponentReferenceDetails Class](topic6356.md)   
[ReleasedComponentReferenceDetails Members](topic6357.md)


