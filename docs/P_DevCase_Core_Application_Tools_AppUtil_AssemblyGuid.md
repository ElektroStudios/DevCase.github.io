# AppUtil.AssemblyGuid Property 
 

Gets the Guid of the current application.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Guid AssemblyGuid { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property AssemblyGuid As Guid
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As Guid

value = AppUtil.AssemblyGuid

```

**C++**<br />
``` C++
public:
static property Guid AssemblyGuid {
	Guid get ();
}
```

**F#**<br />
``` F#
static member AssemblyGuid : Guid with get

```


#### Property Value
Type: Guid<br />The resulting Guid.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim guid As Guid = AssemblyGuid
Console.WriteLine(guid.ToString())
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_AppUtil">AppUtil Class</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />