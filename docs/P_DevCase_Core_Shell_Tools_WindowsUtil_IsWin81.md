# WindowsUtil.IsWin81 Property 
 

Gets a value that determines whether the current operating system is `Windows 8.1`.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsWin81 { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property IsWin81 As Boolean
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = WindowsUtil.IsWin81

```

**C++**<br />
``` C++
public:
static property bool IsWin81 {
	bool get ();
}
```

**F#**<br />
``` F#
static member IsWin81 : bool with get

```


#### Property Value
Type: Boolean<br />A value that determines whether the current operating system is `Windows 8.1`.

## Examples
This is a code example. 
**VB**<br />
``` VB
If IsWin81 Then
    Throw New PlatformNotSupportedException("This application cannot run under Windows 8.1.")
End If
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_WindowsUtil">WindowsUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />