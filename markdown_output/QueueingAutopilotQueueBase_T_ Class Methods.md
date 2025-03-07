Collapse All Expand All Members Options: Show All  Members Options: Filtered   
---  
DriveWorks SDK Documentation  |   
---|---  
QueueingAutopilotQueueBase<T> Class Methods   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications.Autopilot.Extensibility Namespace](topic1633.md) : QueueingAutopilotQueueBase<T> Class  
---  
  
Include Inherited Members    
Include Protected Members    


Glossary Item Box

For a list of all members of this type, see [QueueingAutopilotQueueBase<T> members](topic1926.md).

# Public Methods

| Name| Description  
---|---|---  
Public Method| [BeginStart](topic1931.md)| Begins the process of starting the queue on a new thread.   
Public Method| [BeginStop](topic1932.md)| Begins the process of stopping the queue.   
Top

# Protected Methods

| Name| Description  
---|---|---  
Protected Method| [Execute](topic1933.md)| Must be overridden to perform the main work of the queue on the specified item.   
Protected Method| [Initialize](topic1934.md)| Can be overridden to perform custom initialization when the queue is created.   
Protected Method| [InitializeThread](topic1935.md)| Can be overridden to customize the thread that is used for execution.   
Protected Method| [OnStart](topic1936.md)| Can be overridden to perform one-time initialization when the queue is started.   
Protected Method| [OnStop](topic1937.md)| Can be overridden to perform shutdown when the queue is stopped.   
Protected Method| [QueueItem](topic1938.md)| Queues the specified work item.   
Top

# See Also

#### Reference

[QueueingAutopilotQueueBase<T> Class](topic1925.md)   
[DriveWorks.Applications.Autopilot.Extensibility Namespace](topic1633.md)


