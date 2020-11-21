# AppShellExecuteInfo.Path Property 
 

Gets or sets a string (in the form of a semicolon-separated list of directories) to append to the PATH environment variable when an application is launched by calling `ShellExecuteEx`. 

 It is the fully qualified path to the .exe.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string Path { get; set; }
```

**VB**<br />
``` VB
Public Property Path As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As AppShellExecuteInfo
Dim value As String

value = instance.Path

instance.Path = value
```

**C++**<br />
``` C++
public:
property String^ Path {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
member Path : string with get, set

```


#### Property Value
Type: String<br />A string (in the form of a semicolon-separated list of directories) to append to the PATH environment variable when an application is launched by calling `ShellExecuteEx`.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_AppShellExecuteInfo">AppShellExecuteInfo Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />