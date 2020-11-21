# UserConfig.FilePath Property 
 

Gets the user-config filepath.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Settings_Tools">DevCase.Core.Application.Settings.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string FilePath { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property FilePath As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As String

value = UserConfig.FilePath

```

**C++**<br />
``` C++
public:
static property String^ FilePath {
	String^ get ();
}
```

**F#**<br />
``` F#
static member FilePath : string with get

```


#### Property Value
Type: String<br />The user-config filepath.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim filepath As String = FilePath
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Settings_Tools_UserConfig">UserConfig Class</a><br /><a href="N_DevCase_Core_Application_Settings_Tools">DevCase.Core.Application.Settings.Tools Namespace</a><br />