# PowerUtil Methods
 

The <a href="T_DevCase_Core_Shell_Tools_PowerUtil">PowerUtil</a> type exposes the following members.


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
<a href="#powerutil-methods">Back to Top</a>

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
<a href="#powerutil-methods">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_PowerUtil">PowerUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />