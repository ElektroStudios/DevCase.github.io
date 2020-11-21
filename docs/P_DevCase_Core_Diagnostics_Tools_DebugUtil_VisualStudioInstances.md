# DebugUtil.VisualStudioInstances Property 
 

Gets a collection of the Visual Studio instances that are running on this PC.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<DTE2> VisualStudioInstances { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property VisualStudioInstances As IEnumerable(Of DTE2)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As IEnumerable(Of DTE2)

value = DebugUtil.VisualStudioInstances

```

**C++**<br />
``` C++
public:
static property IEnumerable<DTE2^>^ VisualStudioInstances {
	IEnumerable<DTE2^>^ get ();
}
```

**F#**<br />
``` F#
static member VisualStudioInstances : IEnumerable<DTE2> with get

```


#### Property Value
Type: IEnumerable(DTE2)<br />An IEnumerable(T) that contains the running Visual Studio instances, if any.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim instances As IEnumerable(Of DTE2) = VisualStudioInstances()
```


## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_Tools_DebugUtil">DebugUtil Class</a><br /><a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools Namespace</a><br />