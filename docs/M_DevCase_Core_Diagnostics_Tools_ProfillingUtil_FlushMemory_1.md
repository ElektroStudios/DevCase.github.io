# ProfillingUtil.FlushMemory Method (IntPtr)
 

Flushes the memory of the current process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool FlushMemory(
	IntPtr handle
)
```

**VB**<br />
``` VB
Public Shared Function FlushMemory ( 
	handle As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim handle As IntPtr
Dim returnValue As Boolean

returnValue = ProfillingUtil.FlushMemory(handle)
```

**C++**<br />
``` C++
public:
static bool FlushMemory(
	IntPtr handle
)
```

**F#**<br />
``` F#
static member FlushMemory : 
        handle : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>handle</dt><dd>Type: System.IntPtr<br />The target process handle.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the function succeeds, `false` (`False` in Visual Basic) otherwise.

## Examples
This is a code example. 
**VB**<br />
``` VB
FlushMemory(Me.Handle)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_Tools_ProfillingUtil">ProfillingUtil Class</a><br /><a href="Overload_DevCase_Core_Diagnostics_Tools_ProfillingUtil_FlushMemory">FlushMemory Overload</a><br /><a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools Namespace</a><br />