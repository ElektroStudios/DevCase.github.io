# AppShellExecuteInfo.UseUrl Property 
 

Gets or sets a value indicating whether the application can accept a URL (instead of a file name) on the command line. 

 Applications that can open documents directly from the internet, like web browsers and media players, should set this entry. 

 When the `ShellExecuteEx` function starts an application and the `UseUrl=True` value is not set, `ShellExecuteEx` downloads the document to a local file and invokes the handler on the local copy.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool UseUrl { get; set; }
```

**VB**<br />
``` VB
Public Property UseUrl As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As AppShellExecuteInfo
Dim value As Boolean

value = instance.UseUrl

instance.UseUrl = value
```

**C++**<br />
``` C++
public:
property bool UseUrl {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
member UseUrl : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the application can accept a URL (instead of a file name) on the command line; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_AppShellExecuteInfo">AppShellExecuteInfo Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />