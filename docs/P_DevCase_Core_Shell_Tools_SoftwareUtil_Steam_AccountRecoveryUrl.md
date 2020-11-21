# SoftwareUtil.Steam.AccountRecoveryUrl Property 
 

Gets the official Steam url about regaining access to a lost Steam account, the url is in the same language of the Steam client installed on the current Operating System. 

 Not available for all languages.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string AccountRecoveryUrl { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property AccountRecoveryUrl As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As String

value = SoftwareUtil.Steam.AccountRecoveryUrl

```

**C++**<br />
``` C++
public:
static property String^ AccountRecoveryUrl {
	String^ get ();
}
```

**F#**<br />
``` F#
static member AccountRecoveryUrl : string with get

```


#### Property Value
Type: String<br />If Steam is not installed, gets the url in english language, otherwise, gets the url in the detected language.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_SoftwareUtil_Steam">SoftwareUtil.Steam Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />