Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
GetStandardStoreName(String,Nullable<StandardStoreOptions>) Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Forms.DataModel Namespace](topic9371.md) > [DynamicProperty Class](topic9398.md) > [GetStandardStoreName Method](topic9412.md) : GetStandardStoreName(String,Nullable<StandardStoreOptions>) Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_controlName_
    The name of the control that has the store option.

_opt_
    The standard store option to get the reference for.

Glossary Item Box

Gets the reference name that will be used for the specified control name and store option combination. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Overloads Shared Function GetStandardStoreName( _
       ByVal _controlName_ As String, _
       ByVal _opt_ As Nullable(Of StandardStoreOptions) _
    ) As String  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim controlName As String
    Dim opt As Nullable(Of StandardStoreOptions)
    Dim value As String
     
    value = [DynamicProperty](topic9398.md).GetStandardStoreName(controlName, opt)  
  
C#|   
---|---  
      
    
    public static string GetStandardStoreName( 
       string _controlName_ ,
       Nullable<StandardStoreOptions> _opt_
    )  
  
#### Parameters

 _controlName_
    The name of the control that has the store option.
_opt_
    The standard store option to get the reference for.

#### Return Value

Returns the store name for the specified combination, when opt has a value, otherwise null.

# Exceptions

Exception| Description  
---|---  
System.ArgumentOutOfRangeException| Thrown when unknown opt value is given.  
  
# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[DynamicProperty Class](topic9398.md)   
[DynamicProperty Members](topic9399.md)   
[Overload List](topic9412.md)


