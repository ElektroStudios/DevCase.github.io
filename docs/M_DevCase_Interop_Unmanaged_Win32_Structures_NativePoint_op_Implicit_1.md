# NativePoint&nbsp;Implicit Conversion (Point to NativePoint)
 

Performs an implicit conversion from Point to <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">NativePoint</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static implicit operator NativePoint (
	Point pt
)
```

**VB**<br />
``` VB
Public Shared Widening Operator CType ( 
	pt As Point
) As NativePoint
```

**VB Usage**<br />
``` VB Usage
Dim input As Point
Dim output As NativePoint

output = CType(input, NativePoint)
```

**C++**<br />
``` C++
static implicit operator NativePoint (
	Point pt
)
```

**F#**<br />
``` F#

```


#### Parameters
&nbsp;<dl><dt>pt</dt><dd>Type: System.Drawing.Point<br />The Point.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">NativePoint</a><br />The resulting <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">NativePoint</a>.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">NativePoint Structure</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint_op_Implicit">Implicit Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />