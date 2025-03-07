Collapse All Expand All Members Options: Show All  Members Options: Filtered   
---  
DriveWorks SDK Documentation  |   
---|---  
PollingConnectorBase Class Members   
See Also Properties Methods Events [Send Feedback](mailto:apisupport@driveworks.co.uk?subject=Documentation Feedback: topic1914.md)  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications.Autopilot.Extensibility Namespace](topic1633.md) : PollingConnectorBase Class  
---  
  
Include Inherited Members    
Include Protected Members  


Glossary Item Box

The following tables list the members exposed by [PollingConnectorBase](topic1914.md).

# Protected Properties

| Name| Description  
---|---|---  
![Protected Property](dotnetimages/protectedProperty.gif)| [Application](topic1845.md)| Gets the hosting application. (Inherited from [DriveWorks.Applications.Autopilot.Extensibility.ConnectorBase](topic1834.md))  
![Protected Property](dotnetimages/protectedProperty.gif)| [Automation](topic1846.md)| Gets the specification automation service. (Inherited from [DriveWorks.Applications.Autopilot.Extensibility.ConnectorBase](topic1834.md))  
![Protected Property](dotnetimages/protectedProperty.gif)| [IsStopping](topic1923.md)| Determines whether the connector is running and has been asked to stop.   
![Protected Property](dotnetimages/protectedProperty.gif)| [PollingInterval](topic1924.md)| Gets/sets the polling interval.   
Top

# Protected Methods

| Name| Description  
---|---|---  
Protected Method| [OnExecute](topic1920.md)| Performs the work on each polling interval.   
Protected Method| [OnInitialize](topic1840.md)| When overridden in a derived class, performs the work required to initialize the connector. (Inherited from [DriveWorks.Applications.Autopilot.Extensibility.ConnectorBase](topic1834.md))  
Protected Method| [OnStart](topic1921.md)| Overridden. Performs the work required to start the connector.   
Protected Method| [OnStop](topic1922.md)| Overridden. Provides the work required to stop the connector.   
Protected Method| [RaiseStarted](topic1843.md)| Raises the [Started](topic1847.md) event. (Inherited from [DriveWorks.Applications.Autopilot.Extensibility.ConnectorBase](topic1834.md))  
Protected Method| [RaiseStopped](topic1844.md)| Raises the [Stopped](topic1848.md) event. (Inherited from [DriveWorks.Applications.Autopilot.Extensibility.ConnectorBase](topic1834.md))  
Top

# Public Events

| Name| Description  
---|---|---  
![Public Event](dotnetimages/publicEvent.gif)| [Started](topic1847.md)| Occurs when a connector has started. (Inherited from [DriveWorks.Applications.Autopilot.Extensibility.ConnectorBase](topic1834.md))  
![Public Event](dotnetimages/publicEvent.gif)| [Stopped](topic1848.md)| Occurs when a connector has stopped. (Inherited from [DriveWorks.Applications.Autopilot.Extensibility.ConnectorBase](topic1834.md))  
Top

# See Also

#### Reference

[PollingConnectorBase Class](topic1914.md)   
[DriveWorks.Applications.Autopilot.Extensibility Namespace](topic1633.md)


