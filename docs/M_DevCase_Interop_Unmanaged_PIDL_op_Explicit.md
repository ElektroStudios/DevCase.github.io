# PIDL&nbsp;Explicit Conversion (PIDL to IntPtr)
 

Performs an explicit conversion from <a href="T_DevCase_Interop_Unmanaged_PIDL">PIDL</a> to IntPtr.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged">DevCase.Interop.Unmanaged</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static explicit operator IntPtr (
	PIDL pidl
)
```

**VB**<br />
``` VB
Public Shared Narrowing Operator CType ( 
	pidl As PIDL
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim input As PIDL
Dim output As IntPtr

output = CType(input, IntPtr)
```

**C++**<br />
``` C++
static explicit operator IntPtr (
	PIDL^ pidl
)
```

**F#**<br />
``` F#

```


#### Parameters
&nbsp;<dl><dt>pidl</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_PIDL">DevCase.Interop.Unmanaged.PIDL</a><br />The source <a href="T_DevCase_Interop_Unmanaged_PIDL">PIDL</a>.</dd></dl>

#### Return Value
Type: IntPtr<br />The result of the conversion.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_PIDL">PIDL Class</a><br /><a href="N_DevCase_Interop_Unmanaged">DevCase.Interop.Unmanaged Namespace</a><br />