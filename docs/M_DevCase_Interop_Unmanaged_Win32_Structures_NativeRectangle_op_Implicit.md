# NativeRectangle&nbsp;Implicit Conversion (NativeRectangle to Rectangle)
 

Performs an implicit conversion from <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> to Rectangle.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static implicit operator Rectangle (
	NativeRectangle rect
)
```

**VB**<br />
``` VB
Public Shared Widening Operator CType ( 
	rect As NativeRectangle
) As Rectangle
```

**VB Usage**<br />
``` VB Usage
Dim input As NativeRectangle
Dim output As Rectangle

output = CType(input, Rectangle)
```

**C++**<br />
``` C++
static implicit operator Rectangle (
	NativeRectangle rect
)
```

**F#**<br />
``` F#

```


#### Parameters
&nbsp;<dl><dt>rect</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">DevCase.Interop.Unmanaged.Win32.Structures.NativeRectangle</a><br />The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a>.</dd></dl>

#### Return Value
Type: Rectangle<br />The resulting Rectangle.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle Structure</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle_op_Implicit">Implicit Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />