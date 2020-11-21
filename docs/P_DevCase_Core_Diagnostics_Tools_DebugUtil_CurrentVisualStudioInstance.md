# DebugUtil.CurrentVisualStudioInstance Property 
 

Gets a DTE2 object that represents the current Visual Studio instance that is running this project.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DTE2 CurrentVisualStudioInstance { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property CurrentVisualStudioInstance As DTE2
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As DTE2

value = DebugUtil.CurrentVisualStudioInstance

```

**C++**<br />
``` C++
public:
static property DTE2^ CurrentVisualStudioInstance {
	DTE2^ get ();
}
```

**F#**<br />
``` F#
static member CurrentVisualStudioInstance : DTE2 with get

```


#### Property Value
Type: DTE2<br />A DTE2 object that represents the current Visual Studio instance that is running this project.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim instance As DTE2 = CurrentVisualStudioInstance()
```


## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_Tools_DebugUtil">DebugUtil Class</a><br /><a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools Namespace</a><br />