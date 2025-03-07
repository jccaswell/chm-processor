Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
FlowPropertyData Constructor(String,Boolean,Object,String)   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Transactions Namespace](topic12835.md) > [FlowPropertyData Class](topic12873.md) > [FlowPropertyData Constructor](topic12879.md) : FlowPropertyData Constructor(String,Boolean,Object,String)  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_name_
    The name of the property.

_isBound_
    True if the property is bound to a rule, otherwise false.

_value_
    The value or rule.

_comment_
    The comment if the property is bound to a rule.

Glossary Item Box

Initializes a new instance of the [FlowPropertyData](topic12873.md) class. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function New( _
       ByVal _name_ As String, _
       ByVal _isBound_ As Boolean, _
       ByVal _value_ As Object, _
       ByVal _comment_ As String _
    )  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim name As String
    Dim isBound As Boolean
    Dim value As Object
    Dim comment As String
     
    Dim instance As New [FlowPropertyData](topic12873.md)(name, isBound, value, comment)  
  
C#|   
---|---  
      
    
    public FlowPropertyData( 
       string _name_ ,
       bool _isBound_ ,
       object _value_ ,
       string _comment_
    )  
  
#### Parameters

 _name_
    The name of the property.
_isBound_
    True if the property is bound to a rule, otherwise false.
_value_
    The value or rule.
_comment_
    The comment if the property is bound to a rule.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[FlowPropertyData Class](topic12873.md)   
[FlowPropertyData Members](topic12874.md)   
[Overload List](topic12879.md)


