# NativeSize&nbsp;Implicit Conversion (Size to NativeSize)
 

Performs an implicit conversion from Size to <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeSize">NativeSize</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static implicit operator NativeSize (
	Size size
)
```

**VB**<br />
``` VB
Public Shared Widening Operator CType ( 
	size As Size
) As NativeSize
```

**VB Usage**<br />
``` VB Usage
Dim input As Size
Dim output As NativeSize

output = CType(input, NativeSize)
```

**C++**<br />
``` C++
static implicit operator NativeSize (
	Size size
)
```

**F#**<br />
``` F#

```


#### Parameters
&nbsp;<dl><dt>size</dt><dd>Type: System.Drawing.Size<br />The Size.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeSize">NativeSize</a><br />The resulting <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeSize">NativeSize</a>.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeSize">NativeSize Structure</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_Structures_NativeSize_op_Implicit">Implicit Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />