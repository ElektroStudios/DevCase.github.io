# DebugUtil Class
 

Contains debugging related utilities.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Diagnostics.Tools.DebugUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class DebugUtil : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class DebugUtil
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As DebugUtil
```

**C++**<br />
``` C++
public ref class DebugUtil sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type DebugUtil =  
    class
        inherit AestheticObject
    end
```

The DebugUtil type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Diagnostics_Tools_DebugUtil_BuildOutputWindow">BuildOutputWindow</a></td><td>
Gets the Build window output of the Visual Studio instance that hosts the current application.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Diagnostics_Tools_DebugUtil_CurrentMember">CurrentMember</a></td><td>
Gets the current executing member in the stack trace of the application.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Diagnostics_Tools_DebugUtil_CurrentVisualStudioInstance">CurrentVisualStudioInstance</a></td><td>
Gets a DTE2 object that represents the current Visual Studio instance that is running this project.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Diagnostics_Tools_DebugUtil_DebugOutputWindow">DebugOutputWindow</a></td><td>
Gets the Debug window output of the Visual Studio instance that hosts the current application.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Diagnostics_Tools_DebugUtil_IsAntiNetworkDebugProtectionEnabled">IsAntiNetworkDebugProtectionEnabled</a></td><td>
Gets a value that indicates whether Anti-Network Debugging protection is enabled for the current application. 

 Anti-Network Debugging protection can be enabled by calling <a href="M_DevCase_Core_Diagnostics_Tools_DebugUtil_EnableAntiNetworkDebugProtection">EnableAntiNetworkDebugProtection(Action)</a> method, and disabled by calling <a href="M_DevCase_Core_Diagnostics_Tools_DebugUtil_DisableAntiNetworkDebugProtection">DisableAntiNetworkDebugProtection()</a> method.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Diagnostics_Tools_DebugUtil_IsAntiSandboxProtectionEnabled">IsAntiSandboxProtectionEnabled</a></td><td>
Gets a value that indicates whether Anti-Sandbox environment protection is enabled for the current application. 

 Anti-Sandbox environment protection can be enabled by calling <a href="M_DevCase_Core_Diagnostics_Tools_DebugUtil_EnableAntiSandboxProtection">EnableAntiSandboxProtection(Action)</a> method, and disabled by calling <a href="M_DevCase_Core_Diagnostics_Tools_DebugUtil_DisableAntiSandboxProtection">DisableAntiSandboxProtection()</a> method.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Diagnostics_Tools_DebugUtil_VisualStudioInstances">VisualStudioInstances</a></td><td>
Gets a collection of the Visual Studio instances that are running on this PC.</td></tr></table>&nbsp;
<a href="#debugutil-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Diagnostics_Tools_DebugUtil_CauseBSOD">CauseBSOD</a></td><td>
Causes a BSOD (Blue Screen of Death). 

 Please be aware that after causing the BSOD, the operating system will stop responding and a computer shutdown/restart will be required.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Diagnostics_Tools_DebugUtil_ClearBuildOutputWindow">ClearBuildOutputWindow</a></td><td>
Clears the Build window output of the Visual Studio instance that hosts the current application.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Diagnostics_Tools_DebugUtil_ClearDebugOutputWindow">ClearDebugOutputWindow</a></td><td>
Clears the Debug window output of the Visual Studio instance that hosts the current application.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Diagnostics_Tools_DebugUtil_DisableAntiNetworkDebugProtection">DisableAntiNetworkDebugProtection</a></td><td>
Disables the Anti-Network Debugging protection previously enabled by <a href="M_DevCase_Core_Diagnostics_Tools_DebugUtil_EnableAntiNetworkDebugProtection">EnableAntiNetworkDebugProtection(Action)</a> method for the current application.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Diagnostics_Tools_DebugUtil_DisableAntiSandboxProtection">DisableAntiSandboxProtection</a></td><td>
Disables the Anti-Sandbox environment protection previously enabled by <a href="M_DevCase_Core_Diagnostics_Tools_DebugUtil_EnableAntiSandboxProtection">EnableAntiSandboxProtection(Action)</a> method for the current application.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Diagnostics_Tools_DebugUtil_EnableAntiNetworkDebugProtection">EnableAntiNetworkDebugProtection</a></td><td>
Enables Anti-Network Debugging protection for the current application. 

 This Anti-Network Debugging protection supports only these network protocol analyzers: 

 • Fiddler 

 • Wireshark 

 • WPE Pro</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Diagnostics_Tools_DebugUtil_EnableAntiSandboxProtection">EnableAntiSandboxProtection</a></td><td>
Enables Anti-Sandbox environment protection for the current application. 

 This Anti-Sandbox environment protection supports only these Sandbox environments: 

 • Sandboxie</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Diagnostics_Tools_DebugUtil_EvaluateStructureInstanceSize">EvaluateStructureInstanceSize</a></td><td>
Determines whether the instance size (in bytes) of a Structure (ValueType) is smaller and/or greater than the size recommended by Microsoft guidelines.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Diagnostics_Tools_DebugUtil_IsFiddlerRunning">IsFiddlerRunning</a></td><td>
Determines whether `Fiddler` program is running on the current machine. 

`Fiddler` is a network protocol analyzer for Windows operating system.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Diagnostics_Tools_DebugUtil_IsRunningOnSandboxie">IsRunningOnSandboxie</a></td><td>
Determines whether the current application is running under `Sandboxie` environment. 

`Sandboxie` is a sandbox software for application isolation, it can run a program in a virtual sandbox environment without writing to the hard drive, so, it can block malicious software, viruses, ransom-ware and zero day threats by isolating such attacks in the sandbox.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Diagnostics_Tools_DebugUtil_IsVisualStudioHostingProcessAttached">IsVisualStudioHostingProcessAttached</a></td><td>
Determines whether the Visual Studio Hosting Process (vshost.exe) is attached on the current process.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Diagnostics_Tools_DebugUtil_IsWiresharkRunning">IsWiresharkRunning</a></td><td>
Determines whether `Wireshark` program is running on the current machine. 

`Wireshark` is a network protocol analyzer for Windows operating system.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Diagnostics_Tools_DebugUtil_IsWPERunning">IsWPERunning</a></td><td>
Determines whether `WPE Pro` (`Winsock Packet Editor`) program is running on the current machine. 

`WPE Pro` is a network protocol analyzer for Windows operating system.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Diagnostics_Tools_DebugUtil_MiniDumpToFile">MiniDumpToFile(Process, FileInfo, MiniDumpType)</a></td><td>
Dumps debug information from a process to a local file. 

 With this, you can dump the entire allocated memory by a external process.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Diagnostics_Tools_DebugUtil_MiniDumpToFile_1">MiniDumpToFile(Process, String, MiniDumpType)</a></td><td>
Dumps debug information from a process to a local file. 

 With this, you can dump the entire allocated memory by a external process.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Diagnostics_Tools_DebugUtil_MiniDumpToMemoryStream">MiniDumpToMemoryStream</a></td><td>
Dumps debug information from a process to a MemoryStream. 

 With this, you can dump the entire allocated memory by a external process.</td></tr></table>&nbsp;
<a href="#debugutil-class">Back to Top</a>

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
<a href="#debugutil-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools Namespace</a><br />