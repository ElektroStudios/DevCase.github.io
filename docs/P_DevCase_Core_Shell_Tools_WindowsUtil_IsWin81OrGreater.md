# WindowsUtil.IsWin81OrGreater Property 
 

Gets a value that determines whether the current operating system is `Windows 8.1`, or greater.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsWin81OrGreater { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property IsWin81OrGreater As Boolean
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = WindowsUtil.IsWin81OrGreater

```

**C++**<br />
``` C++
public:
static property bool IsWin81OrGreater {
	bool get ();
}
```

**F#**<br />
``` F#
static member IsWin81OrGreater : bool with get

```


#### Property Value
Type: Boolean<br />A value that determines whether the current operating system is `Windows 8.1`, or greater.

## Examples
This is a code example. 
**VB**<br />
``` VB
If Not IsWin81OrGreater Then
    Throw New PlatformNotSupportedException("This application cannot run under the current Windows version.")
End If
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_WindowsUtil">WindowsUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />