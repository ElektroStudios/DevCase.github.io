# AppUtil Class
 

Contains application related utilities.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.Tools.AppUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class AppUtil : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class AppUtil
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As AppUtil
```

**C++**<br />
``` C++
public ref class AppUtil sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type AppUtil =  
    class
        inherit AestheticObject
    end
```

The AppUtil type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Application_Tools_AppUtil_AssemblyGuid">AssemblyGuid</a></td><td>
Gets the Guid of the current application.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Application_Tools_AppUtil_BrowserEmulationMode">BrowserEmulationMode</a></td><td>
Gets or sets the Internet Explorer browser emulation mode for the current application.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Application_Tools_AppUtil_DirectoryPath">DirectoryPath</a></td><td>
Gets the directory path where the current assembly is stored.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Application_Tools_AppUtil_FileExtension">FileExtension</a></td><td>
Gets the file extension of the current assembly.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Application_Tools_AppUtil_Filename">Filename</a></td><td>
Gets the filename, without extension, of the current assembly.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Application_Tools_AppUtil_Fullpath">Fullpath</a></td><td>
Gets the full path of the current assembly.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Application_Tools_AppUtil_IsCurrentAssemblyInGAC">IsCurrentAssemblyInGAC</a></td><td>
Gets a value indicating whether the current executing assembly is installed in GAC (Global Assembly Cache).</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Application_Tools_AppUtil_LoadedAssemblies">LoadedAssemblies</a></td><td>
Gets the loaded assemblies of the current assembly.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Application_Tools_AppUtil_ProcessArchitecture">ProcessArchitecture</a></td><td>
Determines whether the architecture of the current process is 32 or 64 Bits.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Application_Tools_AppUtil_ProcessErrorMode">ProcessErrorMode</a></td><td>
Gets or sets a value that controls whether the system will handle the specified types of serious errors or whether the current process will handle them.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Application_Tools_AppUtil_ProcessPriority">ProcessPriority</a></td><td>
Gets or sets the overall priority category for the associated process.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Application_Tools_AppUtil_ReferencedAssemblies">ReferencedAssemblies</a></td><td>
Gets the referenced assemblies of the current assembly.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Application_Tools_AppUtil_SelfBytes">SelfBytes</a></td><td>
Gets the bytes of the local file that points to the running assembly.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Application_Tools_AppUtil_ThreadErrorMode">ThreadErrorMode</a></td><td>
Gets or sets a value that controls whether the system will handle the specified types of serious errors or whether the current process will handle them.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Application_Tools_AppUtil_Threads">Threads</a></td><td>
Gets the set of threads that are running in the current process.</td></tr></table>&nbsp;
<a href="#apputil-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Tools_AppUtil_AddRelativeAssemblyReferencePaths">AddRelativeAssemblyReferencePaths</a></td><td>
Adds the specified directories in the private application's path, to look for referenced assemblies.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Tools_AppUtil_AppOpenWithRegister">AppOpenWithRegister</a></td><td>
Registers an application for `OpenWith` features through the `HKEY_CLASSES_ROOT\Applications\ApplicationName.exe` registry subkey.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Tools_AppUtil_AppOpenWithUnregister">AppOpenWithUnregister</a></td><td>
Unregisters an application that has been registered for `OpenWith` features using the <a href="M_DevCase_Core_Application_Tools_AppUtil_AppOpenWithRegister">AppOpenWithRegister(AppOpenWithInfo)</a> method.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Tools_AppUtil_AppShellExecuteRegister">AppShellExecuteRegister</a></td><td>
Registers an application for `ShellExecute` features through `HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\App Paths` registry subkey.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Tools_AppUtil_AppShellExecuteUnregister">AppShellExecuteUnregister</a></td><td>
Unregisters an application that has been registered for `ShellExecute` features using the <a href="M_DevCase_Core_Application_Tools_AppUtil_AppShellExecuteRegister">AppShellExecuteRegister(AppShellExecuteInfo)</a> method.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Tools_AppUtil_ComputeSelfHash__1">ComputeSelfHash(T)</a></td><td>
Computes a hash code for the main executable file of the running application.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Tools_AppUtil_CreateMutex">CreateMutex(MutexScope, String, Boolean)</a></td><td>
Initializes a new instance of the Mutex class with a Boolean value that indicates whether the calling thread should have initial ownership of the Mutex, and a String that is the name of the mutex.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Tools_AppUtil_CreateMutex_1">CreateMutex(MutexScope, String, Boolean, Boolean)</a></td><td>
Initializes a new instance of the Mutex class with a Boolean value that indicates whether the calling thread should have initial ownership of the Mutex, a String that is the name of the mutex, and a Boolean variable that, when the method returns, indicates whether the calling thread was granted initial ownership of the Mutex.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Tools_AppUtil_CreateMutex_2">CreateMutex(MutexScope, String, Boolean, Boolean, MutexSecurity)</a></td><td>
Initializes a new instance of the Mutex class with a Boolean value that indicates whether the calling thread should have initial ownership of the Mutex, a String that is the name of the mutex, a Boolean variable that, when the method returns, indicates whether the calling thread was granted initial ownership of the Mutex, and the access control security to be applied to the Mutex.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Tools_AppUtil_DeleteSelfApplication">DeleteSelfApplication()</a></td><td>
Deletes itself the application executable file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Tools_AppUtil_DeleteSelfApplication_1">DeleteSelfApplication(TimeSpan)</a></td><td>
Deletes itself the application executable file after the specified time interval.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Tools_AppUtil_GetFirstRunFlag">GetFirstRunFlag</a></td><td>
Gets the first run flag registry.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Tools_AppUtil_GetIEBrowserEmulationMode">GetIEBrowserEmulationMode(Process, RegistryScope)</a></td><td>
Gets the Internet Explorer browser emulation mode for the specified process.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Tools_AppUtil_GetIEBrowserEmulationMode_1">GetIEBrowserEmulationMode(String, RegistryScope)</a></td><td>
Gets the Internet Explorer browser emulation mode for the specified process.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Tools_AppUtil_SetFirstRunFlag">SetFirstRunFlag</a></td><td>
Writes a registry value with name `IsFirstRun` under the `HKCU\SOFTWARE\{Application Name}\` registry key to evaluate whether this is the first run of the current application in any next application runs. 

 The flag is</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Tools_AppUtil_SetIEBrowserEmulationMode">SetIEBrowserEmulationMode(Process, RegistryScope, IEBrowserEmulationMode)</a></td><td>
Sets the Internet Explorer browser emulation mode for the specified process.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Tools_AppUtil_SetIEBrowserEmulationMode_1">SetIEBrowserEmulationMode(String, RegistryScope, IEBrowserEmulationMode)</a></td><td>
Sets the Internet Explorer browser emulation mode for the specified process.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Tools_AppUtil_SetThreadPriority_1">SetThreadPriority(ThreadPriority)</a></td><td>
Sets the priority for the current thread.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Tools_AppUtil_SetThreadPriority">SetThreadPriority(Int32, ThreadPriorityLevel)</a></td><td>
Sets the priority for the target thread.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Tools_AppUtil_Sleep">Sleep(Int32)</a></td><td>
Blocks the current thread for the specified amount of time, in milliseconds.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Tools_AppUtil_Sleep_1">Sleep(TimeSpan)</a></td><td>
Blocks the current thread for the specified amount of time.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Tools_AppUtil_SleepRandom">SleepRandom(Int32)</a></td><td>
Blocks the current thread for a random amount of time, in milliseconds, between `1` and the specified maximum value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Tools_AppUtil_SleepRandom_2">SleepRandom(TimeSpan)</a></td><td>
Blocks the current thread for a random amount of time, between `1` millisecond and the specified maximum values.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Tools_AppUtil_SleepRandom_1">SleepRandom(Int32, Int32)</a></td><td>
Blocks the current thread for a random amount of time, in milliseconds, between the specified minimum and maximum values.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Tools_AppUtil_SleepRandom_3">SleepRandom(TimeSpan, TimeSpan)</a></td><td>
Blocks the current thread for a random amount of time between the specified minimum and maximum values.</td></tr></table>&nbsp;
<a href="#apputil-class">Back to Top</a>

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
<a href="#apputil-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />