# AppShellExecuteInfo Class
 

Represents the `ShellExecute` specific information for an application registration through `HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\App Paths` registry subkey.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.AppShellExecuteInfo<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class AppShellExecuteInfo : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class AppShellExecuteInfo
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As AppShellExecuteInfo
```

**C++**<br />
``` C++
public ref class AppShellExecuteInfo sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type AppShellExecuteInfo =  
    class
        inherit AestheticObject
    end
```

The AppShellExecuteInfo type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_AppShellExecuteInfo__ctor">AppShellExecuteInfo(FileInfo)</a></td><td>
Initializes a new instance of the AppShellExecuteInfo class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_AppShellExecuteInfo__ctor_1">AppShellExecuteInfo(String)</a></td><td>
Initializes a new instance of the AppShellExecuteInfo class.</td></tr></table>&nbsp;
<a href="#appshellexecuteinfo-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_AppShellExecuteInfo_Default">Default</a></td><td>
Gets the application name provided in the `(Default)` registry entry. 

 If necessary, the `ShellExecuteEx` function adds the extension when searching `App Paths` registry subkey.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_AppShellExecuteInfo_DontUseDesktopChangeRouter">DontUseDesktopChangeRouter</a></td><td>
Gets or sets a value mandatory for debugger applications to avoid file dialog deadlocks when debugging the Windows Explorer process. 

 Setting the <a href="P_DevCase_Core_Application_AppShellExecuteInfo_DontUseDesktopChangeRouter">DontUseDesktopChangeRouter</a> entry produces a slightly less efficient handling of the change notifications, however.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_AppShellExecuteInfo_DropTarget">DropTarget</a></td><td>
Gets or sets the CLSID of an object (usually a local server rather than an in-process server) that implements `IDropTarget` interface. 

 By default, when the drop target is an executable file, and no DropTarget value is provided, the Shell converts the list of dropped files into a command-line parameter and passes it to `ShellExecuteEx` through lpParameters.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_AppShellExecuteInfo_Path">Path</a></td><td>
Gets or sets a string (in the form of a semicolon-separated list of directories) to append to the PATH environment variable when an application is launched by calling `ShellExecuteEx`. 

 It is the fully qualified path to the .exe.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_AppShellExecuteInfo_SupportedProtocols">SupportedProtocols</a></td><td>
Gets or sets a string that contains the URL protocol schemes for a given key. This can contain multiple registry values to indicate which schemes are supported. 

 This string follows the format of `scheme1:scheme2`. 

 If this list is Not empty, `file:` will be added To the String. 

 This protocol Is implicitly supported When <a href="P_DevCase_Core_Application_AppShellExecuteInfo_SupportedProtocols">SupportedProtocols</a> is defined.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_AppShellExecuteInfo_UseUrl">UseUrl</a></td><td>
Gets or sets a value indicating whether the application can accept a URL (instead of a file name) on the command line. 

 Applications that can open documents directly from the internet, like web browsers and media players, should set this entry. 

 When the `ShellExecuteEx` function starts an application and the `UseUrl=True` value is not set, `ShellExecuteEx` downloads the document to a local file and invokes the handler on the local copy.</td></tr></table>&nbsp;
<a href="#appshellexecuteinfo-class">Back to Top</a>

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
<a href="#appshellexecuteinfo-class">Back to Top</a>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ee872121%28v=vs.85%29.aspx#appPaths" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ee872121%28v=vs.85%29.aspx#appPaths</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim file As New FileInfo("C:\Program Files\MyApplication.exe")
Dim info As New AppShellExecuteInfo(file)

With info
    .Path = String.Format("{0}\", file.DirectoryName)
    .DropTarget = Guid.Empty
    .UseUrl = False
    .DontUseDesktopChangeRouter = False
    .SupportedProtocols = String.Empty
End With
```


## See Also


#### Reference
<a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />