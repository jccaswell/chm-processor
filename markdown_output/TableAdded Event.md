TableAdded Event   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [GroupDataTables Class](topic3136.md) : TableAdded Event  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Raised when a new table is added to the group. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Event TableAdded As EventHandler(Of ValueEventArgs(Of GroupDataTable))  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [GroupDataTables](topic3136.md)
    Dim handler As EventHandler(Of ValueEventArgs(Of GroupDataTable))
     
    AddHandler instance.TableAdded, handler  
  
C#|   
---|---  
      
    
    public event EventHandler<ValueEventArgs<GroupDataTable>> TableAdded  
  
# Event Data

The event handler receives an argument of type [ValueEventArgs<T>](topic5843.md) containing data related to this event. The following **ValueEventArgs <T>** properties provide information specific to this event.

Property| Description  
---|---  
[Value](topic5850.md)| Gets the item specific to this event.   
  
# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[GroupDataTables Class](topic3136.md)   
[GroupDataTables Members](topic3137.md)


