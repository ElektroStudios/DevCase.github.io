# SoftwareUtil.Winamp.ExecutablePath Property 
 

Gets the filepath of the Winamp executabl file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string ExecutablePath { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property ExecutablePath As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As String

value = SoftwareUtil.Winamp.ExecutablePath

```

**C++**<br />
``` C++
public:
static property String^ ExecutablePath {
	String^ get ();
}
```

**F#**<br />
``` F#
static member ExecutablePath : string with get

```


#### Property Value
Type: String<br />If Winamp is installed, the return value is the filepath of the Winamp executabl file. 

 If Winamp process is not installed, the return value is a null reference (`Nothing` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_SoftwareUtil_Winamp">SoftwareUtil.Winamp Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />