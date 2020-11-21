# IProgressDialog.SetProgress64 Method 
 

Updates the progress dialog box with the current state of the operation.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
void SetProgress64(
	ulong completed,
	ulong total
)
```

**VB**<br />
``` VB
Sub SetProgress64 ( 
	completed As ULong,
	total As ULong
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IProgressDialog
Dim completed As ULong
Dim total As ULong

instance.SetProgress64(completed, total)
```

**C++**<br />
``` C++
void SetProgress64(
	unsigned long long completed, 
	unsigned long long total
)
```

**F#**<br />
``` F#
abstract SetProgress64 : 
        completed : uint64 * 
        total : uint64 -> unit 

```


#### Parameters
&nbsp;<dl><dt>completed</dt><dd>Type: System.UInt64<br />An application-defined value that indicates what proportion of the operation has been completed at the time the method was called.</dd><dt>total</dt><dd>Type: System.UInt64<br />An application-defined value that specifies what value *completed* will have when the operation is complete.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IProgressDialog">IProgressDialog Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />