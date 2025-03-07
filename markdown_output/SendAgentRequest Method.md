SendAgentRequest Method   
  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks Namespace](topic2159.md) > [Group Class](topic2958.md) : SendAgentRequest Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_agentName_
    The name of the agent to send the request message to.

_message_
    The request to send to the specified agent. Object type MUST be marked with System.SerializableAttribute.

Glossary Item Box

Attempts to send a request message to the specified agent. Then waits for a reply and returns that result. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Public Function SendAgentRequest( _
       ByVal _agentName_ As String, _
       ByVal _message_ As Object _
    ) As Object  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [Group](topic2958.md)
    Dim agentName As String
    Dim message As Object
    Dim value As Object
     
    value = instance.SendAgentRequest(agentName, message)  
  
C#|   
---|---  
      
    
    public object SendAgentRequest( 
       string _agentName_ ,
       object _message_
    )  
  
#### Parameters

 _agentName_
    The name of the agent to send the request message to.
_message_
    The request to send to the specified agent. Object type MUST be marked with System.SerializableAttribute.

#### Return Value

The reply value from the agent.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[Group Class](topic2958.md)   
[Group Members](topic2959.md)


