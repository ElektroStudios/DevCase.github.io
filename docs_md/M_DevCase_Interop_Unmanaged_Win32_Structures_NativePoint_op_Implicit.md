# NativePoint&nbsp;Implicit Conversion (NativePoint to Point)
 

Performs an implicit conversion from <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">NativePoint</a> to Point.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static implicit operator Point (
	NativePoint pt
)
```

**VB**<br />
``` VB
Public Shared Widening Operator CType ( 
	pt As NativePoint
) As Point
```

**VB Usage**<br />
``` VB Usage
Dim input As NativePoint
Dim output As Point

output = CType(input, Point)
```

**C++**<br />
``` C++
static implicit operator Point (
	NativePoint pt
)
```

**F#**<br />
``` F#

```


#### Parameters
&nbsp;<dl><dt>pt</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">DevCase.Interop.Unmanaged.Win32.Structures.NativePoint</a><br />The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">NativePoint</a>.</dd></dl>

#### Return Value
Type: Point<br />The resulting Point.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">NativePoint Structure</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint_op_Implicit">Implicit Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />