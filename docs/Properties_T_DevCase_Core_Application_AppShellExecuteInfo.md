# AppShellExecuteInfo Properties
 

The <a href="T_DevCase_Core_Application_AppShellExecuteInfo">AppShellExecuteInfo</a> type exposes the following members.


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
<a href="#appshellexecuteinfo-properties">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_AppShellExecuteInfo">AppShellExecuteInfo Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />