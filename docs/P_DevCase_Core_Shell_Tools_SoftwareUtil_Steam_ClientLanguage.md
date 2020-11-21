# SoftwareUtil.Steam.ClientLanguage Property 
 

Gets the language of the Steam client installed on the current Operating System.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string ClientLanguage { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property ClientLanguage As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As String

value = SoftwareUtil.Steam.ClientLanguage

```

**C++**<br />
``` C++
public:
static property String^ ClientLanguage {
	String^ get ();
}
```

**F#**<br />
``` F#
static member ClientLanguage : string with get

```


#### Property Value
Type: String<br />If Steam is not installed, the return value is a empty string, otherwise, the client language.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_SoftwareUtil_Steam">SoftwareUtil.Steam Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />