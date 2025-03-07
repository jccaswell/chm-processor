Collapse All Expand All Members Options: Show All  Members Options: Filtered   
---  
DriveWorks SDK Documentation  |   
---|---  
EventReportWriter Class Members   
See Also Properties Methods Events [Send Feedback](mailto:apisupport@driveworks.co.uk?subject=Documentation Feedback: topic10409.md)  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Reporting Namespace](topic10334.md) : EventReportWriter Class  
---  
  
Include Inherited Members    
Include Protected Members  


Glossary Item Box

The following tables list the members exposed by [EventReportWriter](topic10409.md).

# Public Constructors

| Name| Description  
---|---|---  
![Public Constructor](dotnetimages/publicConstructor.gif)| [EventReportWriter Constructor](topic10415.md)| Initializes a new instance of the [EventReportWriter](topic10409.md) type.   
Top

# Public Properties

| Name| Description  
---|---|---  
![Public Property](dotnetimages/publicProperty.gif)| [IsDisposed](topic10492.md)| Determines whether the report writer has been disposed. (Inherited from [DriveWorks.Reporting.ReportWriterBase](topic10476.md))  
![Public Property](dotnetimages/publicProperty.gif)| [ProcessDepth](topic10493.md)| Gets the current depth of processes. (Inherited from [DriveWorks.Reporting.ReportWriterBase](topic10476.md))  
Top

# Public Methods

| Name| Description  
---|---|---  
Public Method| [BeginProcess](topic10416.md)| Overloaded. Overridden. Begins a process.   
Public Method| [EndProcess](topic10419.md)| Overridden. Ends the current process.   
Public Method| [WriteEntry](topic10420.md)| Overridden. Writes a report entry to the report.   
Top

# Protected Methods

| Name| Description  
---|---|---  
Protected Method| [AssertNotDisposed](topic10482.md)| Throws an System.ObjectDisposedException if the object has been disposed. (Inherited from [DriveWorks.Reporting.ReportWriterBase](topic10476.md))  
Protected Method| [Dispose](topic10487.md)| Disposes the report writer and flushes its contents to the report. (Inherited from [DriveWorks.Reporting.ReportWriterBase](topic10476.md))  
Protected Method| [Finalize](topic10489.md)| Handles object finalization. (Inherited from [DriveWorks.Reporting.ReportWriterBase](topic10476.md))  
Protected Method| [Finish](topic10490.md)| Finishes the report, flushing any cached contents to the report if necessary. (Inherited from [DriveWorks.Reporting.ReportWriterBase](topic10476.md))  
Top

# Public Events

| Name| Description  
---|---|---  
![Public Event](dotnetimages/publicEvent.gif)| [EntryWritten](topic10421.md)| Raised when an entry is written.   
![Public Event](dotnetimages/publicEvent.gif)| [ProcessBegun](topic10422.md)| Raised when a process is begun.   
![Public Event](dotnetimages/publicEvent.gif)| [ProcessEnded](topic10423.md)| Raised when a process is ended.   
Top

# See Also

#### Reference

[EventReportWriter Class](topic10409.md)   
[DriveWorks.Reporting Namespace](topic10334.md)


