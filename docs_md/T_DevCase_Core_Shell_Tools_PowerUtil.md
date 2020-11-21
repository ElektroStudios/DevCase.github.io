# PowerUtil Class
 

Contains system powering related utilities.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Shell.Tools.PowerUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class PowerUtil : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class PowerUtil
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As PowerUtil
```

**C++**<br />
``` C++
public ref class PowerUtil sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type PowerUtil =  
    class
        inherit AestheticObject
    end
```

The PowerUtil type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_PowerUtil_ActivePowerPlan">ActivePowerPlan</a></td><td>
Gets or sets the active power plan on the current system.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_PowerUtil_PowerPlans">PowerPlans</a></td><td>
Gets all the power plans available on the current system.</td></tr></table>&nbsp;
<a href="#powerutil-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_PowerUtil_AbortShutdown">AbortShutdown</a></td><td>
Aborts a system shutdown operation that has been initiated (unless a LogOff).</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_PowerUtil_Hibernate">Hibernate</a></td><td>
Sets the system in Hibernate state.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_PowerUtil_HybridShutdown">HybridShutdown</a></td><td>
Shutdowns the specified computer and prepares the system for a faster startup. 

 Use this function only for Windows 8/8.1</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_PowerUtil_LogOff">LogOff</a></td><td>
Shuts down all processes running in the logon session and then logs off the interactive user.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_PowerUtil_PowerOff">PowerOff</a></td><td>
Shutdowns the specified computer and begins powered down.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_PowerUtil_RemoveAwakeSignal">RemoveAwakeSignal</a></td><td>
Removes any previously sent Awake signal. 

 Call this function to return to previous state when the caller thread has finished.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Shell_Tools_PowerUtil_Restart">Restart</a></td><td>
Restarts the specified computer.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_PowerUtil_RestartApps">RestartApps</a></td><td>
Restarts the specified computer, also restarts any applications that have been registered for restart in the system.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Shell_Tools_PowerUtil_SendAwakeSignal">SendAwakeSignal</a></td><td>
Sends an Awake signal to prevent the system from turning off the display and entering into Sleep or Hibernation modes.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_PowerUtil_SetMonitorState">SetMonitorState(MonitorState)</a></td><td>
Sets the state of the monitor.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_PowerUtil_SetMonitorState_1">SetMonitorState(IntPtr, MonitorState)</a></td><td>
Sets the state of the monitor.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_PowerUtil_Shutdown">Shutdown</a></td><td>
Shutdowns the specified computer.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_PowerUtil_Suspend">Suspend</a></td><td>
Sets the system in Suspend state.</td></tr></table>&nbsp;
<a href="#powerutil-class">Back to Top</a>

## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_Core_Shell_Tools_PowerUtil_MaxShutdownTimeout">MaxShutdownTimeout</a></td><td>
The maximum number of seconds to wait before shutting down the computer.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_Core_Shell_Tools_PowerUtil_PowerPlanBalanced">PowerPlanBalanced</a></td><td>
Gets the Balanced PowerPlan.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_Core_Shell_Tools_PowerUtil_PowerPlanMaximumPerformance">PowerPlanMaximumPerformance</a></td><td>
Gets the Maximum Performance PowerPlan.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_Core_Shell_Tools_PowerUtil_PowerPlanMinimumPerformance">PowerPlanMinimumPerformance</a></td><td>
Gets the Minimum Performance PowerPlan.</td></tr></table>&nbsp;
<a href="#powerutil-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo">CanConvertTo(Type)</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo__1">CanConvertTo(T)()</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1">ConvertTo(T)()</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, an exception is thrown.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1_1">ConvertTo(T)(T)</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, returns the specified default value.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#powerutil-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />