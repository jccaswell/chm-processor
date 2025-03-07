Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
DropDownOpening Event   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications Namespace](topic16.md) > [IVirtualSplitCommandButton Interface](topic598.md) : DropDownOpening Event  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Raised when the drop down is opening. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Event DropDownOpening As [VirtualItemsRequestEventHandler](topic1276.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [IVirtualSplitCommandButton](topic598.md)
    Dim handler As [VirtualItemsRequestEventHandler](topic1276.md)
     
    AddHandler instance.DropDownOpening, handler  
  
C#|   
---|---  
      
    
    event [VirtualItemsRequestEventHandler](topic1276.md) DropDownOpening  
  
# Event Data

The event handler receives an argument of type [VirtualItemsRequestEventArgs](topic1192.md) containing data related to this event. The following **VirtualItemsRequestEventArgs** properties provide information specific to this event.

Property| Description  
---|---  
[Items](topic1199.md)| Gets/sets the virtual items which will be used by the sender of the event.   
  
# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[IVirtualSplitCommandButton Interface](topic598.md)   
[IVirtualSplitCommandButton Members](topic599.md)


