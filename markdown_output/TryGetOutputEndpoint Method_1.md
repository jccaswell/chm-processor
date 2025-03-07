TryGetOutputEndpoint Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Specification Namespace](topic10764.md) > [Task Class](topic11629.md) : TryGetOutputEndpoint Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_name_
    The name of the end point to find.

_isNavigation_
    True if the requested end point is a navigation end point.

_output_
    The end point (if found), otherwise a null reference.

Glossary Item Box

Attempts to retrieve the end point with the given name. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Overrides Function TryGetOutputEndpoint( _
       ByVal _name_ As String, _
       ByVal _isNavigation_ As Boolean, _
       ByRef _output_ As [NodeOutput](topic7074.md) _
    ) As Boolean  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [Task](topic11629.md)
    Dim name As String
    Dim isNavigation As Boolean
    Dim output As [NodeOutput](topic7074.md)
    Dim value As Boolean
     
    value = instance.TryGetOutputEndpoint(name, isNavigation, output)  
  
C#|   
---|---  
      
    
    public override bool TryGetOutputEndpoint( 
       string _name_ ,
       bool _isNavigation_ ,
       ref [NodeOutput](topic7074.md) _output_
    )  
  
#### Parameters

 _name_
    The name of the end point to find.
_isNavigation_
    True if the requested end point is a navigation end point.
_output_
    The end point (if found), otherwise a null reference.

#### Return Value

True if the end point was found, otherwise false.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[Task Class](topic11629.md)   
[Task Members](topic11630.md)


