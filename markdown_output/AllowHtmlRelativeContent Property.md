Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
AllowHtmlRelativeContent Property   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [GeneralGroupSettings Class](topic2940.md) : AllowHtmlRelativeContent Property  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Gets/sets whether all files in the same folder as an HTML file (or one of its sub folders) can be accessed via a browser. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Property AllowHtmlRelativeContent As Boolean  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [GeneralGroupSettings](topic2940.md)
    Dim value As Boolean
     
    instance.AllowHtmlRelativeContent = value
     
    value = instance.AllowHtmlRelativeContent  
  
C#|   
---|---  
      
    
    public bool AllowHtmlRelativeContent {get; set;}  
  
# Remarks

This is used in Live when serving HTML files.

If this is set to True, any other file that is in the same folder as the HTML file (or one of its sub folders) can be accessed.

If this is set to False, which it is by default, then only the HTML file and any references we find inside of it will be accessible via these URLs.

The only time we expose HTML files is when viewing Specification Documents.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[GeneralGroupSettings Class](topic2940.md)   
[GeneralGroupSettings Members](topic2941.md)


