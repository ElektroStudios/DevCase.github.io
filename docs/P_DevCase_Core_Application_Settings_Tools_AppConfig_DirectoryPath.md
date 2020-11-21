# AppConfig.DirectoryPath Property 
 

Gets the app-config directory path.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Settings_Tools">DevCase.Core.Application.Settings.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string DirectoryPath { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property DirectoryPath As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As String

value = AppConfig.DirectoryPath

```

**C++**<br />
``` C++
public:
static property String^ DirectoryPath {
	String^ get ();
}
```

**F#**<br />
``` F#
static member DirectoryPath : string with get

```


#### Property Value
Type: String<br />The app-config directory path.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim dirpath As String = DirectoryPath
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Settings_Tools_AppConfig">AppConfig Class</a><br /><a href="N_DevCase_Core_Application_Settings_Tools">DevCase.Core.Application.Settings.Tools Namespace</a><br />