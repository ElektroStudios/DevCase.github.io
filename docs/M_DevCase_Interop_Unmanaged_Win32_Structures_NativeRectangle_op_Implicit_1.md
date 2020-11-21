# NativeRectangle&nbsp;Implicit Conversion (Rectangle to NativeRectangle)
 

Performs an implicit conversion from Rectangle to <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static implicit operator NativeRectangle (
	Rectangle rect
)
```

**VB**<br />
``` VB
Public Shared Widening Operator CType ( 
	rect As Rectangle
) As NativeRectangle
```

**VB Usage**<br />
``` VB Usage
Dim input As Rectangle
Dim output As NativeRectangle

output = CType(input, NativeRectangle)
```

**C++**<br />
``` C++
static implicit operator NativeRectangle (
	Rectangle rect
)
```

**F#**<br />
``` F#

```


#### Parameters
&nbsp;<dl><dt>rect</dt><dd>Type: System.Drawing.Rectangle<br />The Rectangle.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a><br />The resulting <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a>.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle Structure</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle_op_Implicit">Implicit Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />