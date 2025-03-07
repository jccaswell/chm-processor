Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
InsertHtmlViewBefore(String,String,String,String,ImageSource,StateFilter,String) Method   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications Namespace](topic16.md) > [IViewRegistrationService Interface](topic578.md) > [InsertHtmlViewBefore Method](topic593.md) : InsertHtmlViewBefore(String,String,String,String,ImageSource,StateFilter,String) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_beforeViewName_
    The name of the view before which to insert the view, or a null reference (Nothing in Visual Basic) to place the view at the beginning of the views at the current level.

_name_
    The culture-invariant name of the view.

_title_
    The localized title of the view.

_parent_
    The culture-invariant name of the parent view (see remarks).

_imageSource_
    The source of the image shown in the view manager UI.

_stateFilter_
    A filter which describes which application states the view is included in and/or excluded from.

_htmlPath_
    A URI which identifies the HTML file to load.

Glossary Item Box

Inserts a new view before an existing view. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Overloads Sub InsertHtmlViewBefore( _
       ByVal _beforeViewName_ As String, _
       ByVal _name_ As String, _
       ByVal _title_ As String, _
       ByVal _parent_ As String, _
       ByVal _imageSource_ As ImageSource, _
       ByVal _stateFilter_ As [StateFilter](topic1077.md), _
       ByVal _htmlPath_ As String _
    )   
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [IViewRegistrationService](topic578.md)
    Dim beforeViewName As String
    Dim name As String
    Dim title As String
    Dim parent As String
    Dim imageSource As ImageSource
    Dim stateFilter As [StateFilter](topic1077.md)
    Dim htmlPath As String
     
    instance.InsertHtmlViewBefore(beforeViewName, name, title, parent, imageSource, stateFilter, htmlPath)  
  
C#|   
---|---  
      
    
    void InsertHtmlViewBefore( 
       string _beforeViewName_ ,
       string _name_ ,
       string _title_ ,
       string _parent_ ,
       ImageSource _imageSource_ ,
       [StateFilter](topic1077.md) _stateFilter_ ,
       string _htmlPath_
    )  
  
#### Parameters

 _beforeViewName_
    The name of the view before which to insert the view, or a null reference (Nothing in Visual Basic) to place the view at the beginning of the views at the current level.
_name_
    The culture-invariant name of the view.
_title_
    The localized title of the view.
_parent_
    The culture-invariant name of the parent view (see remarks).
_imageSource_
    The source of the image shown in the view manager UI.
_stateFilter_
    A filter which describes which application states the view is included in and/or excluded from.
_htmlPath_
    A URI which identifies the HTML file to load.

# Remarks

Views are organized into two levels, a parent view generally categorizes and describes its children (this view is usually an HTML view), and the children provide access to capabilities related to the parent (these are usually control views).

Views may not be nested deeper than two levels.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[IViewRegistrationService Interface](topic578.md)   
[IViewRegistrationService Members](topic579.md)   
[Overload List](topic593.md)


