# ProcessUtil Class
 

Contains related Process utilities.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.IPC.Tools.ProcessUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class ProcessUtil : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class ProcessUtil
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As ProcessUtil
```

**C++**<br />
``` C++
public ref class ProcessUtil sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type ProcessUtil =  
    class
        inherit AestheticObject
    end
```

The ProcessUtil type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_CloseProcesses">CloseProcesses</a></td><td>
Closes all the ocurrences found of running processes with the specified name.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_ForEachProcessByName">ForEachProcessByName</a></td><td>
Performs an action on all the Process objects found of running processes with the specified name.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_ForEachProcessByNameGet__1">ForEachProcessByNameGet(T)</a></td><td>
Performs an action on all the Process objects found of running processes with the specified name.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_GetCurrentProcessCriticalState">GetCurrentProcessCriticalState</a></td><td>
Determines whether the caller process is considered `critical`.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_GetCurrentProcessPrivilegeState">GetCurrentProcessPrivilegeState(ProcessPrivileges)</a></td><td>
Gets the state of a privilege from the current process.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_GetCurrentProcessPrivilegeState_1">GetCurrentProcessPrivilegeState(String, ProcessPrivileges)</a></td><td>
Gets the state of a privilege from the current process on the target computer.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_GetProcessCpuPercentUsage">GetProcessCpuPercentUsage(Process)</a></td><td>
Gets the CPU percentage usage for the specified Process.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_GetProcessCpuPercentUsage_1">GetProcessCpuPercentUsage(Int32)</a></td><td>
Gets the CPU percentage usage for the process with the specified process id (pid).</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_GetProcessCpuPercentUsageAsync">GetProcessCpuPercentUsageAsync(Process)</a></td><td>
Asynchronously gets the CPU percentage usage for the specified Process.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_GetProcessCpuPercentUsageAsync_1">GetProcessCpuPercentUsageAsync(Int32)</a></td><td>
Asynchronously gets the CPU percentage usage for the specified Process.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_GetProcessCriticalState">GetProcessCriticalState</a></td><td>
Determines whether the specified process is considered critical.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_GetProcessPerformanceCounter">GetProcessPerformanceCounter(Process, String)</a></td><td>
Gets a PerformanceCounter of the categry name "Process" with the specified counter name for the specified process.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_GetProcessPerformanceCounter_1">GetProcessPerformanceCounter(Int32, String)</a></td><td>
Gets a PerformanceCounter of the categry name "Process" with the specified counter name for the process with the specified process id (pid).</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_GetProcessPrivilegeState">GetProcessPrivilegeState(Process, ProcessPrivileges)</a></td><td>
Gets the state of a privilege from the specified process.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_GetProcessPrivilegeState_1">GetProcessPrivilegeState(Int32, ProcessPrivileges)</a></td><td>
Gets the state of a privilege from the specified process.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_GetProcessPrivilegeState_2">GetProcessPrivilegeState(String, Process, ProcessPrivileges)</a></td><td>
Gets the state of a privilege from the specified process on the target computer.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_GetProcessPrivilegeState_3">GetProcessPrivilegeState(String, Int32, ProcessPrivileges)</a></td><td>
Gets the state of a privilege from the specified process on the target computer.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_GetProcessSecurityDescriptor">GetProcessSecurityDescriptor(Process)</a></td><td>
Gets the security descriptor of the specified process.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_GetProcessSecurityDescriptor_1">GetProcessSecurityDescriptor(Int32)</a></td><td>
Gets the security descriptor of the specified process.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_GetProcessSecurityDescriptor_2">GetProcessSecurityDescriptor(IntPtr)</a></td><td>
Gets the security descriptor of the specified process.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_GetWmiProcessQuery">GetWmiProcessQuery</a></td><td>
Performs a WMI query to Win32_Process class with the specified condition and returns the result.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_IsRunning">IsRunning</a></td><td>
Determines whether exists at least one running process running with the specified name.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_KillProcess">KillProcess</a></td><td>
Kills the first ocurrence found of a running process with the specified name.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_KillProcesses">KillProcesses</a></td><td>
Kills all the ocurrence found of running processes with the specified name.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_SetCurrentProcessCriticalState">SetCurrentProcessCriticalState</a></td><td>
Sets the critical state for the caller process.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_SetCurrentProcessPrivileges">SetCurrentProcessPrivileges(ProcessPrivileges, PrivilegeStates)</a></td><td>
Enable or disable a process privilege for the current process. 

 Note that this method cannot add or remove privileges for external processes. It can only enable existing privileges that are currently disabled, or disable existing privileges that are currently enabled. 

 Trying to enable or disable a removed privilege will result in a exception. 

 In order to avoid this exception, it is recommended to call <a href="M_DevCase_Core_IPC_Tools_ProcessUtil_GetProcessPrivilegeState">GetProcessPrivilegeState(Process, ProcessPrivileges)</a> to determine whether a privilege is removed before calling this method.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_SetCurrentProcessPrivileges_1">SetCurrentProcessPrivileges(String, ProcessPrivileges, PrivilegeStates)</a></td><td>
Enable or disable a process privilege for the current process. 

 Note that this method cannot add or remove privileges for external processes. It can only enable existing privileges that are currently disabled, or disable existing privileges that are currently enabled. 

 Trying to enable or disable a removed privilege will result in a exception. 

 In order to avoid this exception, it is recommended to call <a href="M_DevCase_Core_IPC_Tools_ProcessUtil_GetProcessPrivilegeState">GetProcessPrivilegeState(Process, ProcessPrivileges)</a> to determine whether a privilege is removed before calling this method.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_SetProcessPrivileges">SetProcessPrivileges(Process, ProcessPrivileges, PrivilegeStates)</a></td><td>
Enable or disable a process privilege for the specified process. 

 Note that this method cannot add or remove privileges for external processes. It can only enable existing privileges that are currently disabled, or disable existing privileges that are currently enabled. 

 Trying to enable or disable a removed privilege will result in a exception. 

 In order to avoid this exception, it is recommended to call <a href="M_DevCase_Core_IPC_Tools_ProcessUtil_GetProcessPrivilegeState">GetProcessPrivilegeState(Process, ProcessPrivileges)</a> to determine whether a privilege is removed before calling this method.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_SetProcessPrivileges_1">SetProcessPrivileges(Int32, ProcessPrivileges, PrivilegeStates)</a></td><td>
Enable or disable a process privilege for the specified process. 

 Note that this method cannot add or remove privileges for external processes. It can only enable existing privileges that are currently disabled, or disable existing privileges that are currently enabled. 

 Trying to enable or disable a removed privilege will result in a exception. 

 In order to avoid this exception, it is recommended to call <a href="M_DevCase_Core_IPC_Tools_ProcessUtil_GetProcessPrivilegeState">GetProcessPrivilegeState(Process, ProcessPrivileges)</a> to determine whether a privilege is removed before calling this method.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_SetProcessPrivileges_2">SetProcessPrivileges(String, Process, ProcessPrivileges, PrivilegeStates)</a></td><td>
Enable or disable a process privilege for the specified process on the target computer. 

 Note that this method cannot add or remove privileges for external processes. It can only enable existing privileges that are currently disabled, or disable existing privileges that are currently enabled. 

 Trying to enable or disable a removed privilege will result in a exception. 

 In order to avoid this exception, it is recommended to call <a href="M_DevCase_Core_IPC_Tools_ProcessUtil_GetProcessPrivilegeState">GetProcessPrivilegeState(Process, ProcessPrivileges)</a> to determine whether a privilege is removed before calling this method.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_SetProcessPrivileges_3">SetProcessPrivileges(String, Int32, ProcessPrivileges, PrivilegeStates)</a></td><td>
Enable or disable a process privilege for the specified process on the target computer. 

 Note that this method cannot add or remove privileges for external processes. It can only enable existing privileges that are currently disabled, or disable existing privileges that are currently enabled. 

 Trying to enable or disable a removed privilege will result in a exception. 

 In order to avoid this exception, it is recommended to call <a href="M_DevCase_Core_IPC_Tools_ProcessUtil_GetProcessPrivilegeState">GetProcessPrivilegeState(Process, ProcessPrivileges)</a> to determine whether a privilege is removed before calling this method.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_SetProcessSecurityDescriptor">SetProcessSecurityDescriptor(Process, RawSecurityDescriptor)</a></td><td>
Sets the security descriptor of the specified process.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_SetProcessSecurityDescriptor_1">SetProcessSecurityDescriptor(Int32, RawSecurityDescriptor)</a></td><td>
Sets the security descriptor of the specified process.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_SetProcessSecurityDescriptor_2">SetProcessSecurityDescriptor(IntPtr, RawSecurityDescriptor)</a></td><td>
Sets the security descriptor of the specified process.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_SleepThread">SleepThread(Int32, TimeSpan)</a></td><td>
Suspends the specified thread for the given amount of time.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_SleepThread_1">SleepThread(IntPtr, TimeSpan)</a></td><td>
Suspends the specified thread for the given amount of time.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_WaitUntilLoaded">WaitUntilLoaded</a></td><td> **Obsolete. **
Blocks the caller thread until te specified process has been fully loaded.</td></tr></table>&nbsp;
<a href="#processutil-class">Back to Top</a>

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
<a href="#processutil-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />