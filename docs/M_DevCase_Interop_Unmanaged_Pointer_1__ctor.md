# Pointer(*T*) Constructor 
 

Initializes a new instance of the Pointer struct.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged">DevCase.Interop.Unmanaged</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Pointer(
	IntPtr address
)
```

**VB**<br />
``` VB
Public Sub New ( 
	address As IntPtr
)
```

**VB Usage**<br />
``` VB Usage
Dim address As IntPtr

Dim instance As New Pointer(address)
```

**C++**<br />
``` C++
public:
Pointer(
	IntPtr address
)
```

**F#**<br />
``` F#
new : 
        address : IntPtr -> Pointer
```


#### Parameters
&nbsp;<dl><dt>address</dt><dd>Type: System.IntPtr<br />The base address of unmanaged memory.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Pointer_1">Pointer(T) Structure</a><br /><a href="N_DevCase_Interop_Unmanaged">DevCase.Interop.Unmanaged Namespace</a><br />