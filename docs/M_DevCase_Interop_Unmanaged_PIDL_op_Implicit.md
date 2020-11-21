# PIDL&nbsp;Implicit Conversion (IntPtr to PIDL)
 

Performs an implicit conversion from IntPtr to <a href="T_DevCase_Interop_Unmanaged_PIDL">PIDL</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged">DevCase.Interop.Unmanaged</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static implicit operator PIDL (
	IntPtr handle
)
```

**VB**<br />
``` VB
Public Shared Widening Operator CType ( 
	handle As IntPtr
) As PIDL
```

**VB Usage**<br />
``` VB Usage
Dim input As IntPtr
Dim output As PIDL

output = CType(input, PIDL)
```

**C++**<br />
``` C++
static implicit operator PIDL^ (
	IntPtr handle
)
```

**F#**<br />
``` F#

```


#### Parameters
&nbsp;<dl><dt>handle</dt><dd>Type: System.IntPtr<br />A handle to a native ITEMIDLIST.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_PIDL">PIDL</a><br />The result of the conversion.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_PIDL">PIDL Class</a><br /><a href="N_DevCase_Interop_Unmanaged">DevCase.Interop.Unmanaged Namespace</a><br />