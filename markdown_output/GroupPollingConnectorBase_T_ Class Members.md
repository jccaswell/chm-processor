Collapse All Expand All Members Options: Show All  Members Options: Filtered   
---  
DriveWorks SDK Documentation  |   
---|---  
GroupPollingConnectorBase<T> Class Members   
See Also Properties Methods Events [Send Feedback](mailto:apisupport@driveworks.co.uk?subject=Documentation Feedback: topic1878.md)  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications.Autopilot.Extensibility Namespace](topic1633.md) : GroupPollingConnectorBase<T> Class  
---  
  
Include Inherited Members    
Include Protected Members  


Glossary Item Box

The following tables list the members exposed by [GroupPollingConnectorBase<T>](topic1878.md).

# Protected Properties

| Name| Description  
---|---|---  
![Protected Property](dotnetimages/protectedProperty.gif)| [Application](topic1872.md)| Gets the hosting application. (Inherited from [DriveWorks.Applications.Autopilot.Extensibility.GroupConnectorBase<T>](topic1857.md))  
![Protected Property](dotnetimages/protectedProperty.gif)| [Automation](topic1873.md)| Gets the specification automation service. (Inherited from [DriveWorks.Applications.Autopilot.Extensibility.GroupConnectorBase<T>](topic1857.md))  
![Protected Property](dotnetimages/protectedProperty.gif)| [AutopilotService](topic1874.md)| Gets the Autopilot service. (Inherited from [DriveWorks.Applications.Autopilot.Extensibility.GroupConnectorBase<T>](topic1857.md))  
![Protected Property](dotnetimages/protectedProperty.gif)| [ConnectorInfo](topic1875.md)| Gets the details for this connector. (Inherited from [DriveWorks.Applications.Autopilot.Extensibility.GroupConnectorBase<T>](topic1857.md))  
![Protected Property](dotnetimages/protectedProperty.gif)| [EventDisplayName](topic1876.md)| Gets the name to use in log events for this connector. (Inherited from [DriveWorks.Applications.Autopilot.Extensibility.GroupConnectorBase<T>](topic1857.md))  
![Protected Property](dotnetimages/protectedProperty.gif)| [PollingInterval](topic1887.md)| Gets/sets the polling interval.   
Top

# Public Methods

| Name| Description  
---|---|---  
Public Method| [GetEditor](topic1864.md)| Gets the editor user interface for this group connector. (Inherited from [DriveWorks.Applications.Autopilot.Extensibility.GroupConnectorBase<T>](topic1857.md))  
Public Method| [SetInformation](topic1868.md)| Sets the connector's information. (Inherited from [DriveWorks.Applications.Autopilot.Extensibility.GroupConnectorBase<T>](topic1857.md))  
Public Method| [Start](topic1869.md)| Starts this connector running. (Inherited from [DriveWorks.Applications.Autopilot.Extensibility.GroupConnectorBase<T>](topic1857.md))  
Public Method| [Stop](topic1870.md)| Stops this connector running. (Inherited from [DriveWorks.Applications.Autopilot.Extensibility.GroupConnectorBase<T>](topic1857.md))  
Top

# Protected Methods

| Name| Description  
---|---|---  
Protected Method| [AddEvent](topic1863.md)| Adds an event into the application log. (Inherited from [DriveWorks.Applications.Autopilot.Extensibility.GroupConnectorBase<T>](topic1857.md))  
Protected Method| [OnExecute](topic1884.md)| Performs the work on each polling interval.   
Protected Method| [OnInformationSet](topic1865.md)| Sets the connector's information. (Inherited from [DriveWorks.Applications.Autopilot.Extensibility.GroupConnectorBase<T>](topic1857.md))  
Protected Method| [OnStart](topic1885.md)| Overridden. Starts the polling thread.   
Protected Method| [OnStop](topic1886.md)| Overridden. Stops the polling thread.   
Protected Method| [StoreInformation](topic1871.md)| When called this will store the current information into this group. (Inherited from [DriveWorks.Applications.Autopilot.Extensibility.GroupConnectorBase<T>](topic1857.md))  
Top

# Public Events

| Name| Description  
---|---|---  
![Public Event](dotnetimages/publicEvent.gif)| [InformationSet](topic1877.md)| Raised when the connector's information has been set. (Inherited from [DriveWorks.Applications.Autopilot.Extensibility.GroupConnectorBase<T>](topic1857.md))  
Top

# See Also

#### Reference

[GroupPollingConnectorBase<T> Class](topic1878.md)   
[DriveWorks.Applications.Autopilot.Extensibility Namespace](topic1633.md)


