# NativeSize&nbsp;Implicit Conversion (NativeSize to Size)
 

Performs an implicit conversion from <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeSize">NativeSize</a> to Size.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static implicit operator Size (
	NativeSize size
)
```

**VB**<br />
``` VB
Public Shared Widening Operator CType ( 
	size As NativeSize
) As Size
```

**VB Usage**<br />
``` VB Usage
Dim input As NativeSize
Dim output As Size

output = CType(input, Size)
```

**C++**<br />
``` C++
static implicit operator Size (
	NativeSize size
)
```

**F#**<br />
``` F#

```


#### Parameters
&nbsp;<dl><dt>size</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeSize">DevCase.Interop.Unmanaged.Win32.Structures.NativeSize</a><br />The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeSize">NativeSize</a>.</dd></dl>

#### Return Value
Type: Size<br />The resulting Size.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeSize">NativeSize Structure</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_Structures_NativeSize_op_Implicit">Implicit Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />