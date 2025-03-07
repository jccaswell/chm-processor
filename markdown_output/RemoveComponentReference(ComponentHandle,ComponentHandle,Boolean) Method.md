RemoveComponentReference(ComponentHandle,ComponentHandle,Boolean) Method   
  
[DriveWorks.SolidWorks Assembly](topic13342.md) > [DriveWorks.SolidWorks Namespace](topic13345.md) > [IComponentManager Interface](topic13385.md) > [RemoveComponentReference Method](topic13404.md) : RemoveComponentReference(ComponentHandle,ComponentHandle,Boolean) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_parentHandle_
    The parent from which to remove the reference.

_childHandle_
    The child to remove from the parent.

_completelyRemove_
    Whether or not to completely remove the component information if no more references remain.

Glossary Item Box

Uncaptures the specified child from the parent and returns the number of places where the child is still used. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Overloads Function RemoveComponentReference( _
       ByVal _parentHandle_ As ComponentHandle, _
       ByVal _childHandle_ As ComponentHandle, _
       ByVal _completelyRemove_ As Boolean _
    ) As Integer  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [IComponentManager](topic13385.md)
    Dim parentHandle As ComponentHandle
    Dim childHandle As ComponentHandle
    Dim completelyRemove As Boolean
    Dim value As Integer
     
    value = instance.RemoveComponentReference(parentHandle, childHandle, completelyRemove)  
  
C#|   
---|---  
      
    
    int RemoveComponentReference( 
       ComponentHandle _parentHandle_ ,
       ComponentHandle _childHandle_ ,
       bool _completelyRemove_
    )  
  
#### Parameters

 _parentHandle_
    The parent from which to remove the reference.
_childHandle_
    The child to remove from the parent.
_completelyRemove_
    Whether or not to completely remove the component information if no more references remain.

#### Return Value

The number of parents which still hold a reference to the child after it is removed.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[IComponentManager Interface](topic13385.md)   
[IComponentManager Members](topic13386.md)   
[Overload List](topic13404.md)


