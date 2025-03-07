Collapse All Expand All Members Options: Show All  Members Options: Filtered   
---  
DriveWorks SDK Documentation  |   
---|---  
PollingAutopilotQueueBase Class Members   
See Also Properties Methods [Send Feedback](mailto:apisupport@driveworks.co.uk?subject=Documentation Feedback: topic1898.md)  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications.Autopilot.Extensibility Namespace](topic1633.md) : PollingAutopilotQueueBase Class  
---  
  
Include Inherited Members    
Include Protected Members  


Glossary Item Box

The following tables list the members exposed by [PollingAutopilotQueueBase](topic1898.md).

# Public Properties

| Name| Description  
---|---|---  
![Public Property](dotnetimages/publicProperty.gif)| [IsStopping](topic1912.md)| Determines whether the queue is in the process of stopping.   
![Public Property](dotnetimages/publicProperty.gif)| [SyncRoot](topic1913.md)| Gets an object which can be use to synchronize access to the queue.   
Top

# Public Methods

| Name| Description  
---|---|---  
Public Method| [BeginStart](topic1904.md)| Begins the process of starting the queue on a new thread.   
Public Method| [BeginStop](topic1905.md)| Begins the process of stopping the queue.   
Top

# Protected Methods

| Name| Description  
---|---|---  
Protected Method| [Execute](topic1906.md)| Must be overridden to perform the main work of the queue.   
Protected Method| [Initialize](topic1907.md)| Can be overridden to perform custom initialization when the queue is created.   
Protected Method| [InitializeThread](topic1908.md)| Can be overridden to customize the thread that is used for execution.   
Protected Method| [OnStart](topic1909.md)| Can be overridden to perform one-time initialization when the queue is started.   
Protected Method| [OnStop](topic1910.md)| Can be overridden to perform shutdown when the queue is stopped.   
Protected Method| [WaitForIntervalOrStopRequest](topic1911.md)| Waits until either the polling interval elapses, or a request to stop is made.   
Top

# See Also

#### Reference

[PollingAutopilotQueueBase Class](topic1898.md)   
[DriveWorks.Applications.Autopilot.Extensibility Namespace](topic1633.md)


