Collapse All Expand All Members Options: Show All  Members Options: Filtered   
---  
DriveWorks SDK Documentation  |   
---|---  
Form Class Members   
See Also Fields Properties Methods Events [Send Feedback](mailto:apisupport@driveworks.co.uk?subject=Documentation Feedback: topic8086.md)  
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Forms Namespace](topic7266.md) : Form Class  
---  
  
Include Inherited Members    
Include Protected Members  


Glossary Item Box

The following tables list the members exposed by [Form](topic8086.md).

# Public Fields

| Name| Description  
---|---|---  
![Public Field](dotnetimages/publicField.gif)![static \(Shared in Visual Basic\)](dotnetimages/static.gif)| [BackgroundColorProperty](topic8102.md)| Provides the property store for the [BackgroundColor](topic8096.md) property.   
![Public Field](dotnetimages/publicField.gif)![static \(Shared in Visual Basic\)](dotnetimages/static.gif)| [OnEnterProperty](topic8103.md)| Provides the property store for the [OnEnter](topic8097.md) property.   
![Public Field](dotnetimages/publicField.gif)![static \(Shared in Visual Basic\)](dotnetimages/static.gif)| [OnNextProperty](topic8104.md)| Provides the property store for the [OnNext](topic8098.md) property.   
![Public Field](dotnetimages/publicField.gif)![static \(Shared in Visual Basic\)](dotnetimages/static.gif)| [OnPreviousProperty](topic8105.md)| Provides the property store for the [OnPrevious](topic8099.md) property.   
![Public Field](dotnetimages/publicField.gif)![static \(Shared in Visual Basic\)](dotnetimages/static.gif)| [ShowStandardNavigationProperty](topic8106.md)| Provides the property store for the [ShowStandardNavigation](topic8100.md) property.   
![Public Field](dotnetimages/publicField.gif)![static \(Shared in Visual Basic\)](dotnetimages/static.gif)| [ShowTaskListProperty](topic8107.md)| Provides the property store for the [ShowTaskList](topic8101.md) property.   
Top

# Public Properties

| Name| Description  
---|---|---  
![Public Property](dotnetimages/publicProperty.gif)| [BackgroundColor](topic8096.md)| Overridden. Gets/sets the background color of the form.   
![Public Property](dotnetimages/publicProperty.gif)| [Controls](topic7695.md)| Gets the collection of controls contained by the control. (Inherited from [DriveWorks.Forms.ContainerControlBase](topic7684.md))  
![Public Property](dotnetimages/publicProperty.gif)| [DefaultFont](topic7696.md)| Gets/sets the default font for all controls on this form. (Inherited from [DriveWorks.Forms.ContainerControlBase](topic7684.md))  
![Public Property](dotnetimages/publicProperty.gif)| [Form](topic7728.md)| Gets the parent form. (Inherited from [DriveWorks.Forms.ControlBase](topic7698.md))  
![Public Property](dotnetimages/publicProperty.gif)| [HasInputValue](topic7729.md)| Returns true if the current control has an input value. A control's input value is the main property of the control, editable through the control's interface. (Inherited from [DriveWorks.Forms.ControlBase](topic7698.md))  
![Public Property](dotnetimages/publicProperty.gif)| [IsDeleted](topic7731.md)| Gets whether or not the current control has been deleted. (Inherited from [DriveWorks.Forms.ControlBase](topic7698.md))  
![Public Property](dotnetimages/publicProperty.gif)| [Metadata](topic7734.md)| Gets/sets the control metadata. (Inherited from [DriveWorks.Forms.ControlBase](topic7698.md))  
![Public Property](dotnetimages/publicProperty.gif)| [Name](topic7735.md)| Gets the control name. (Inherited from [DriveWorks.Forms.ControlBase](topic7698.md))  
![Public Property](dotnetimages/publicProperty.gif)| [OnEnter](topic8097.md)| Gets/sets the name of the macro to run before switching to this form.   
![Public Property](dotnetimages/publicProperty.gif)| [OnNext](topic8098.md)| Gets/sets the name of the macro to run before switching to the next form.   
![Public Property](dotnetimages/publicProperty.gif)| [OnPrevious](topic8099.md)| Gets/sets the name of the macro to run before switching to the previous form.   
![Public Property](dotnetimages/publicProperty.gif)| [Parent](topic7736.md)| Gets/sets the parent control. (Inherited from [DriveWorks.Forms.ControlBase](topic7698.md))  
![Public Property](dotnetimages/publicProperty.gif)| [Project](topic7737.md)| Gets the project to which the form belongs. (Inherited from [DriveWorks.Forms.ControlBase](topic7698.md))  
![Public Property](dotnetimages/publicProperty.gif)| [ShowStandardNavigation](topic8100.md)| Gets/Sets whether the default form navigation is shown.   
![Public Property](dotnetimages/publicProperty.gif)| [ShowTaskList](topic8101.md)| Gets/sets whether the form will display a task list.   
![Public Property](dotnetimages/publicProperty.gif)| [SupportsTooltips](topic7738.md)| Gets whether this control supports tooltips. (Inherited from [DriveWorks.Forms.ControlBase](topic7698.md))  
![Public Property](dotnetimages/publicProperty.gif)| [Tag](topic7740.md)| Gets/sets the control tag. (Inherited from [DriveWorks.Forms.ControlBase](topic7698.md))  
![Public Property](dotnetimages/publicProperty.gif)| [TooltipDuration](topic7741.md)| Gets/sets the duration in seconds that the tooltip remains visible for. (Inherited from [DriveWorks.Forms.ControlBase](topic7698.md))  
![Public Property](dotnetimages/publicProperty.gif)| [TooltipText](topic7742.md)| Gets/sets the text to display in the control's tooltip. (Inherited from [DriveWorks.Forms.ControlBase](topic7698.md))  
Top

# Public Methods

| Name| Description  
---|---|---  
Public Method| [ClearInputValue](topic7705.md)| Clears the input value of the control, if it has one. (Inherited from [DriveWorks.Forms.ControlBase](topic7698.md))  
Public Method| CreateObjRef|  (Inherited from System.MarshalByRefObject)  
Public Method| [CreateRefactorProcess](topic7706.md)| Creates an object capable of refactoring all references to the control from its current name, to the given new name. (Inherited from [DriveWorks.Forms.ControlBase](topic7698.md))  
Public Method| [DeleteControls](topic8092.md)| Overloaded. Deletes the specified control from the form.   
Public Method| [GetAllControls](topic7691.md)| Gets collection of all child controls contained by the control. Including the control children's children. (Inherited from [DriveWorks.Forms.ContainerControlBase](topic7684.md))  
Public Method| [GetDefaultRule](topic7707.md)| Gets the default rule for the control's input property. (Inherited from [DriveWorks.Forms.ControlBase](topic7698.md))  
Public Method| [GetInputValue](topic7708.md)| Returns the current input value of the control, if has one. (Inherited from [DriveWorks.Forms.ControlBase](topic7698.md))  
Public Method| GetLifetimeService|  (Inherited from System.MarshalByRefObject)  
Public Method| [IsValidChild](topic7692.md)| Validates whether the specified control can be added as a child. (Inherited from [DriveWorks.Forms.ContainerControlBase](topic7684.md))  
Public Method| [IsValidParent](topic8095.md)| Overridden. Overridden to prevent parenting the form to any other control.   
Public Method| [Serialize](topic7718.md)| Serializes the control and any contents to the given XML writer. (Inherited from [DriveWorks.Forms.ControlBase](topic7698.md))  
Public Method| [SetInputValue](topic7720.md)| Overloaded. Sets the current input value of the control, if it has one. (Inherited from [DriveWorks.Forms.ControlBase](topic7698.md))  
Public Method| [WithTransientEvent](topic7725.md)| Attaches the given event to the given property of the control so that changes to the property will include the event details, and returns an implementation of System.IDisposable that will detach when it is disposed. (Inherited from [DriveWorks.Forms.ControlBase](topic7698.md))  
Top

# Protected Methods

| Name| Description  
---|---|---  
Protected Method| [AssertInSpecification](topic7704.md)| Throws an invalid operation exception if there is no active specification. (Inherited from [DriveWorks.Forms.ControlBase](topic7698.md))  
Protected Method| MemberwiseClone| Overloaded. (Inherited from System.MarshalByRefObject)  
Protected Method| [OnDataProviderInitialized](topic7710.md)| Called when the DataProvider for this control has been initialized. (Inherited from [DriveWorks.Forms.ControlBase](topic7698.md))  
Protected Method| [OnDeleted](topic7693.md)| Raises the [Deleted](topic7759.md) event. (Inherited from [DriveWorks.Forms.ContainerControlBase](topic7684.md))  
Protected Method| [OnInitialized](topic7712.md)| Raises the [Initialized](topic7760.md) event. (Inherited from [DriveWorks.Forms.ControlBase](topic7698.md))  
Protected Method| [OnParentDefaultFontChanged](topic7713.md)| Gives child controls a chance to update the font properties when the default font changed. (Inherited from [DriveWorks.Forms.ControlBase](topic7698.md))  
Protected Method| [OnValidated](topic7714.md)| Raises the [Validated](topic7764.md) event. (Inherited from [DriveWorks.Forms.ControlBase](topic7698.md))  
Protected Method| [OnValueChanged](topic7715.md)| Raises the [OnValueChanged](topic7715.md) event. (Inherited from [DriveWorks.Forms.ControlBase](topic7698.md))  
Protected Method| [RaiseLayoutChanged](topic7716.md)| Raises the [LayoutChanged](topic7761.md) event. (Inherited from [DriveWorks.Forms.ControlBase](topic7698.md))  
Protected Method| [SerializeCore](topic7694.md)| Overridden to serialize child controls. (Inherited from [DriveWorks.Forms.ContainerControlBase](topic7684.md))  
Protected Method| [TryExecuteOnChangeMacro](topic7723.md)|  (Inherited from [DriveWorks.Forms.ControlBase](topic7698.md))  
Protected Method| [Validate](topic7724.md)| When overridden by a derived control, validates the control's properties after a change. (Inherited from [DriveWorks.Forms.ControlBase](topic7698.md))  
Top

# Public Events

| Name| Description  
---|---|---  
![Public Event](dotnetimages/publicEvent.gif)| [ControlPropertyChanged](topic8108.md)| Raised when a direct child's property has changed.   
![Public Event](dotnetimages/publicEvent.gif)| [ControlsCreated](topic8109.md)| Raised when one or more controls are created.   
![Public Event](dotnetimages/publicEvent.gif)| [ControlsDeleted](topic8110.md)| Raised when one or more controls are deleted.   
![Public Event](dotnetimages/publicEvent.gif)| [CreatingControl](topic8111.md)| Raised when a control is being created.   
![Public Event](dotnetimages/publicEvent.gif)| [Deleted](topic7759.md)| Raised when the control is deleted. (Inherited from [DriveWorks.Forms.ControlBase](topic7698.md))  
![Public Event](dotnetimages/publicEvent.gif)| [Initialized](topic7760.md)| Raised when the control has finished initializing and is now ready to use. (Inherited from [DriveWorks.Forms.ControlBase](topic7698.md))  
![Public Event](dotnetimages/publicEvent.gif)| [LayoutChanged](topic7761.md)| Raised when the top, left, width or height of the control is changed. (Inherited from [DriveWorks.Forms.ControlBase](topic7698.md))  
![Public Event](dotnetimages/publicEvent.gif)| [NameChanged](topic7762.md)| Raised when the name of the control changes. (Inherited from [DriveWorks.Forms.ControlBase](topic7698.md))  
![Public Event](dotnetimages/publicEvent.gif)| [NameValueChanged](topic7763.md)| Raised when the name of the control changes and provides information on the name change (Old name and new name). (Inherited from [DriveWorks.Forms.ControlBase](topic7698.md))  
![Public Event](dotnetimages/publicEvent.gif)| [Validated](topic7764.md)| Raised when the control has had its values validated after one or more value changes. (Inherited from [DriveWorks.Forms.ControlBase](topic7698.md))  
![Public Event](dotnetimages/publicEvent.gif)| [ValueChanged](topic7765.md)| Raised when the value of a property on the control changes. (Inherited from [DriveWorks.Forms.ControlBase](topic7698.md))  
Top

# See Also

#### Reference

[Form Class](topic8086.md)   
[DriveWorks.Forms Namespace](topic7266.md)


