Remove(ReleasedInstance) Method   
  
[DriveWorks.SolidWorks Assembly](topic13342.md) > [DriveWorks.SolidWorks.Components Namespace](topic13925.md) > [ReleasedInstanceCollection Class](topic14954.md) > [Remove Method](topic14962.md) : Remove(ReleasedInstance) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_instance_
    The instance to remove from the collection.

Glossary Item Box

Removes the given instance from the collection. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Overloads Function Remove( _
       ByVal _instance_ As [ReleasedInstance](topic14946.md) _
    ) As Boolean  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [ReleasedInstanceCollection](topic14954.md)
    Dim instance As [ReleasedInstance](topic14946.md)
    Dim value As Boolean
     
    value = instance.Remove(instance)  
  
C#|   
---|---  
      
    
    public bool Remove( 
       [ReleasedInstance](topic14946.md) _instance_
    )  
  
#### Parameters

 _instance_
    The instance to remove from the collection.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[ReleasedInstanceCollection Class](topic14954.md)   
[ReleasedInstanceCollection Members](topic14955.md)   
[Overload List](topic14962.md)


