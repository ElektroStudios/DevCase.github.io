# IProgressDialog.SetProgress Method 
 

Updates the progress dialog box with the current state of the operation.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
void SetProgress(
	uint completed,
	uint total
)
```

**VB**<br />
``` VB
Sub SetProgress ( 
	completed As UInteger,
	total As UInteger
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IProgressDialog
Dim completed As UInteger
Dim total As UInteger

instance.SetProgress(completed, total)
```

**C++**<br />
``` C++
void SetProgress(
	unsigned int completed, 
	unsigned int total
)
```

**F#**<br />
``` F#
abstract SetProgress : 
        completed : uint32 * 
        total : uint32 -> unit 

```


#### Parameters
&nbsp;<dl><dt>completed</dt><dd>Type: System.UInt32<br />An application-defined value that indicates what proportion of the operation has been completed at the time the method was called.</dd><dt>total</dt><dd>Type: System.UInt32<br />An application-defined value that specifies what value *completed* will have when the operation is complete.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IProgressDialog">IProgressDialog Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />