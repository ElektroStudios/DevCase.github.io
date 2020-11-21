# AppUtil.IsCurrentAssemblyInGAC Property 
 

Gets a value indicating whether the current executing assembly is installed in GAC (Global Assembly Cache).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsCurrentAssemblyInGAC { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property IsCurrentAssemblyInGAC As Boolean
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = AppUtil.IsCurrentAssemblyInGAC

```

**C++**<br />
``` C++
public:
static property bool IsCurrentAssemblyInGAC {
	bool get ();
}
```

**F#**<br />
``` F#
static member IsCurrentAssemblyInGAC : bool with get

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the current executing assembly is installed in GAC; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_AppUtil">AppUtil Class</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />