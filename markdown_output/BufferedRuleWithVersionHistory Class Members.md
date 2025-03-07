Collapse All Expand All Members Options: Show All  Members Options: Filtered   
---  
DriveWorks SDK Documentation  |   
---|---  
BufferedRuleWithVersionHistory Class Members   
See Also Properties Methods [Send Feedback](mailto:apisupport@driveworks.co.uk?subject=Documentation Feedback: topic6035.md)  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Abstractions Namespace](topic5939.md) : BufferedRuleWithVersionHistory Class  
---  
  
Include Inherited Members    
Include Protected Members  


Glossary Item Box

The following tables list the members exposed by [BufferedRuleWithVersionHistory](topic6035.md).

# Public Constructors

| Name| Description  
---|---|---  
![Public Constructor](dotnetimages/publicConstructor.gif)| [BufferedRuleWithVersionHistory Constructor](topic6041.md)| Initializes a new instance of the [BufferedRuleWithVersionHistory](topic6035.md) type.   
Top

# Public Properties

| Name| Description  
---|---|---  
![Public Property](dotnetimages/publicProperty.gif)| [Comment](topic6027.md)| Gets/sets the rule comment. (Inherited from [DriveWorks.Abstractions.BufferedRule](topic6017.md))  
![Public Property](dotnetimages/publicProperty.gif)| [Context](topic6028.md)| The rules context for this rule. (Inherited from [DriveWorks.Abstractions.BufferedRule](topic6017.md))  
![Public Property](dotnetimages/publicProperty.gif)| [DisplayName](topic6029.md)| Gets the rule id. (Inherited from [DriveWorks.Abstractions.BufferedRule](topic6017.md))  
![Public Property](dotnetimages/publicProperty.gif)| [Id](topic6030.md)| Gets the invariant identifier of the source rule if it implements [IHasRuleId](topic5957.md), otherwise null (Nothing in VB). (Inherited from [DriveWorks.Abstractions.BufferedRule](topic6017.md))  
![Public Property](dotnetimages/publicProperty.gif)| [IsWritable](topic6031.md)| Determines whether the rule is writable (always returns true). (Inherited from [DriveWorks.Abstractions.BufferedRule](topic6017.md))  
![Public Property](dotnetimages/publicProperty.gif)| [Rule](topic6032.md)| Gets/sets the rule formula. (Inherited from [DriveWorks.Abstractions.BufferedRule](topic6017.md))  
![Public Property](dotnetimages/publicProperty.gif)| [Source](topic6033.md)| Gets the rule which will be buffered. (Inherited from [DriveWorks.Abstractions.BufferedRule](topic6017.md))  
![Public Property](dotnetimages/publicProperty.gif)| [Type](topic6034.md)| Gets the rule type. (Inherited from [DriveWorks.Abstractions.BufferedRule](topic6017.md))  
Top

# Public Methods

| Name| Description  
---|---|---  
Public Method| [Flush](topic6024.md)| Flushes the buffered values to the rule which is being buffered. (Inherited from [DriveWorks.Abstractions.BufferedRule](topic6017.md))  
Public Method| [GetVersionHistory](topic6042.md)| Gets the version history for the rule.   
Public Method| [SetRuleAndComment](topic6026.md)| Sets the rule and comment at the same time. (Inherited from [DriveWorks.Abstractions.BufferedRule](topic6017.md))  
Top

# Protected Methods

| Name| Description  
---|---|---  
Protected Method| [FlushCore](topic6025.md)|  (Inherited from [DriveWorks.Abstractions.BufferedRule](topic6017.md))  
Top

# See Also

#### Reference

[BufferedRuleWithVersionHistory Class](topic6035.md)   
[DriveWorks.Abstractions Namespace](topic5939.md)


