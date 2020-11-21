# AppUtil.Filename Property 
 

Gets the filename, without extension, of the current assembly.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string Filename { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property Filename As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As String

value = AppUtil.Filename

```

**C++**<br />
``` C++
public:
static property String^ Filename {
	String^ get ();
}
```

**F#**<br />
``` F#
static member Filename : string with get

```


#### Property Value
Type: String<br />The filename, without extension, of the current assembly.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim filename As String = Filename
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_AppUtil">AppUtil Class</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />