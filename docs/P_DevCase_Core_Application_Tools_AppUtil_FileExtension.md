# AppUtil.FileExtension Property 
 

Gets the file extension of the current assembly.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string FileExtension { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property FileExtension As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As String

value = AppUtil.FileExtension

```

**C++**<br />
``` C++
public:
static property String^ FileExtension {
	String^ get ();
}
```

**F#**<br />
``` F#
static member FileExtension : string with get

```


#### Property Value
Type: String<br />The file extension of the current assembly.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim fileExt As String = FileExtension
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_AppUtil">AppUtil Class</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />