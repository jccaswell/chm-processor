Collapse All Expand All Members Options: Show All  Members Options: Filtered   
---  
DriveWorks SDK Documentation  |   
---|---  
GroupConnectorBase<T> Class Members   
See Also Properties Methods Events [Send Feedback](mailto:apisupport@driveworks.co.uk?subject=Documentation Feedback: topic1857.md)  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications.Autopilot.Extensibility Namespace](topic1633.md) : GroupConnectorBase<T> Class  
---  
  
Include Inherited Members    
Include Protected Members  


Glossary Item Box

The following tables list the members exposed by [GroupConnectorBase<T>](topic1857.md).

# Protected Properties

| Name| Description  
---|---|---  
![Protected Property](dotnetimages/protectedProperty.gif)| [Application](topic1872.md)| Gets the hosting application.   
![Protected Property](dotnetimages/protectedProperty.gif)| [Automation](topic1873.md)| Gets the specification automation service.   
![Protected Property](dotnetimages/protectedProperty.gif)| [AutopilotService](topic1874.md)| Gets the Autopilot service.   
![Protected Property](dotnetimages/protectedProperty.gif)| [ConnectorInfo](topic1875.md)| Gets the details for this connector.   
![Protected Property](dotnetimages/protectedProperty.gif)| [EventDisplayName](topic1876.md)| Gets the name to use in log events for this connector.   
Top

# Public Methods

| Name| Description  
---|---|---  
Public Method| [GetEditor](topic1864.md)| Gets the editor user interface for this group connector.   
Public Method| [SetInformation](topic1868.md)| Sets the connector's information.   
Public Method| [Start](topic1869.md)| Starts this connector running.   
Public Method| [Stop](topic1870.md)| Stops this connector running.   
Top

# Protected Methods

| Name| Description  
---|---|---  
Protected Method| [AddEvent](topic1863.md)| Adds an event into the application log.   
Protected Method| [OnInformationSet](topic1865.md)| Sets the connector's information.   
Protected Method| [OnStart](topic1866.md)| Performs the work required to start the connector.   
Protected Method| [OnStop](topic1867.md)| Provides the work required to stop the connector.   
Protected Method| [StoreInformation](topic1871.md)| When called this will store the current information into this group.   
Top

# Public Events

| Name| Description  
---|---|---  
![Public Event](dotnetimages/publicEvent.gif)| [InformationSet](topic1877.md)| Raised when the connector's information has been set.   
Top

# See Also

#### Reference

[GroupConnectorBase<T> Class](topic1857.md)   
[DriveWorks.Applications.Autopilot.Extensibility Namespace](topic1633.md)


