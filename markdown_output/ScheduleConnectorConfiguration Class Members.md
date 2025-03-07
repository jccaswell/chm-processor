ScheduleConnectorConfiguration Class Members   
See Also Properties Methods [Send Feedback](mailto:apisupport@driveworks.co.uk?subject=Documentation Feedback: topic6851.md)  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Connectors.Schedule Namespace](topic6848.md) : ScheduleConnectorConfiguration Class  
---  
  
Include Inherited Members    
Include Protected Members  


Glossary Item Box

The following tables list the members exposed by [ScheduleConnectorConfiguration](topic6851.md).

# Public Constructors

| Name| Description  
---|---|---  
![Public Constructor](dotnetimages/publicConstructor.gif)| [ScheduleConnectorConfiguration Constructor](topic6857.md)|   
Top

# Public Properties

| Name| Description  
---|---|---  
![Public Property](dotnetimages/publicProperty.gif)| [CronExpression](topic6860.md)| Get/Sets the cron expression that will be used.   
![Public Property](dotnetimages/publicProperty.gif)| [EnabledMachineNames](topic3094.md)| Get/sets A pipe bar delimited list of machine names that have the connector enabled. (Inherited from [DriveWorks.GroupConnectorInformation](topic3084.md))  
![Public Property](dotnetimages/publicProperty.gif)| [Id](topic3095.md)| Gets the identifier value for the connector. (Inherited from [DriveWorks.GroupConnectorInformation](topic3084.md))  
![Public Property](dotnetimages/publicProperty.gif)| [Name](topic3096.md)| Gets/sets the unique name for the connector. (Inherited from [DriveWorks.GroupConnectorInformation](topic3084.md))  
![Public Property](dotnetimages/publicProperty.gif)| [RepeatAmount](topic6861.md)| Get/Sets the amount to repeat on an interval.   
![Public Property](dotnetimages/publicProperty.gif)| [RepeatDays](topic6862.md)| Get/Sets the days the schedule will be repeated on.   
![Public Property](dotnetimages/publicProperty.gif)| [RepeatEndTime](topic6863.md)| Get/Sets the end time that the schedule will repeat to.   
![Public Property](dotnetimages/publicProperty.gif)| [RepeatInterval](topic6864.md)| Get/Sets the Repeat Interval that will be used.   
![Public Property](dotnetimages/publicProperty.gif)| [RepeatStartTime](topic6865.md)| Get/Sets the start time that the schedule will repeat from.   
![Public Property](dotnetimages/publicProperty.gif)| [RunOnceDate](topic6866.md)| Get/Sets the date that the schedule will run once.   
![Public Property](dotnetimages/publicProperty.gif)| [Schedule](topic6867.md)| Get/Sets which schedule type in use.   
![Public Property](dotnetimages/publicProperty.gif)| [Task](topic6868.md)| Get/Sets the Task that will be executed.   
![Public Property](dotnetimages/publicProperty.gif)| [TaskArguments](topic6869.md)| Get/Sets the TaskArguments that will be used.   
![Public Property](dotnetimages/publicProperty.gif)| [TimerInterval](topic6870.md)| Gets/Sets the time in seconds for the period of time to wait between executing a task.   
Top

# Protected Properties

| Name| Description  
---|---|---  
![Protected Property](dotnetimages/protectedProperty.gif)| [Data](topic3093.md)| Gets/sets Value used by connector containing configuration information. (Inherited from [DriveWorks.GroupConnectorInformation](topic3084.md))  
Top

# Public Methods

| Name| Description  
---|---|---  
Public Method| CreateObjRef|  (Inherited from System.MarshalByRefObject)  
Public Method| [GetClone](topic3091.md)| Creates a cloned version of this object. (Inherited from [DriveWorks.GroupConnectorInformation](topic3084.md))  
Public Method| GetLifetimeService|  (Inherited from System.MarshalByRefObject)  
Top

# Protected Methods

| Name| Description  
---|---|---  
Protected Method| [EnsureDataStored](topic6858.md)| Overridden.   
Protected Method| MemberwiseClone| Overloaded. (Inherited from System.MarshalByRefObject)  
Protected Method| [OnInitialized](topic6859.md)| Overridden.   
Top

# See Also

#### Reference

[ScheduleConnectorConfiguration Class](topic6851.md)   
[DriveWorks.Connectors.Schedule Namespace](topic6848.md)


