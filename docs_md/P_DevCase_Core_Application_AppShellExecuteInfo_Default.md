# AppShellExecuteInfo.Default Property 
 

Gets the application name provided in the `(Default)` registry entry. 

 If necessary, the `ShellExecuteEx` function adds the extension when searching `App Paths` registry subkey.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string Default { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property Default As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As AppShellExecuteInfo
Dim value As String

value = instance.Default

```

**C++**<br />
``` C++
public:
property String^ Default {
	String^ get ();
}
```

**F#**<br />
``` F#
member Default : string with get

```


#### Property Value
Type: String<br />The application name provided in the (Default) entry.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_AppShellExecuteInfo">AppShellExecuteInfo Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />