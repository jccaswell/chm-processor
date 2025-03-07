StateFilter Constructor(Guid[],Guid[])   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications Namespace](topic16.md) > [StateFilter Class](topic1077.md) > [StateFilter Constructor](topic1083.md) : StateFilter Constructor(Guid[],Guid[])  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_includedStates_
    The states in which the filtered entity is included.

_excludedStates_
    The states from which the filtered enttity is excluded.

Glossary Item Box

Initializes a new instance of the [StateFilter](topic1077.md) type. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function New( _
       ByVal _includedStates_() As Guid, _
       ByVal _excludedStates_() As Guid _
    )  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim includedStates() As Guid
    Dim excludedStates() As Guid
     
    Dim instance As New [StateFilter](topic1077.md)(includedStates, excludedStates)  
  
C#|   
---|---  
      
    
    public StateFilter( 
       Guid[] _includedStates_ ,
       Guid[] _excludedStates_
    )  
  
#### Parameters

 _includedStates_
    The states in which the filtered entity is included.
_excludedStates_
    The states from which the filtered enttity is excluded.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[StateFilter Class](topic1077.md)   
[StateFilter Members](topic1078.md)   
[Overload List](topic1083.md)


