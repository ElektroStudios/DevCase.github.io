# DebugUtil.BuildOutputWindow Property 
 

Gets the Build window output of the Visual Studio instance that hosts the current application.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string BuildOutputWindow { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property BuildOutputWindow As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As String

value = DebugUtil.BuildOutputWindow

```

**C++**<br />
``` C++
public:
static property String^ BuildOutputWindow {
	String^ get ();
}
```

**F#**<br />
``` F#
static member BuildOutputWindow : string with get

```


#### Property Value
Type: String<br />The Build window output of the Visual Studio instance that hosts the current application.

## Examples
This is a code example. 
**VB**<br />
``` VB
Clipboard.SetText(BuildOutputWindow)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_Tools_DebugUtil">DebugUtil Class</a><br /><a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools Namespace</a><br />