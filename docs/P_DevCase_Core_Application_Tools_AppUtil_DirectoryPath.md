# AppUtil.DirectoryPath Property 
 

Gets the directory path where the current assembly is stored.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

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

value = AppUtil.DirectoryPath

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
Type: String<br />The directory path where the current assembly is stored.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim dirpath As String = DirectoryPath
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_AppUtil">AppUtil Class</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />