# PIDL Constructor (IntPtr, Boolean, Boolean)
 

Initializes a new instance of the <a href="T_DevCase_Interop_Unmanaged_PIDL">PIDL</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged">DevCase.Interop.Unmanaged</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public PIDL(
	IntPtr pidl,
	bool clone = false,
	bool ownsHandle = true
)
```

**VB**<br />
``` VB
Public Sub New ( 
	pidl As IntPtr,
	Optional clone As Boolean = false,
	Optional ownsHandle As Boolean = true
)
```

**VB Usage**<br />
``` VB Usage
Dim pidl As IntPtr
Dim clone As Boolean
Dim ownsHandle As Boolean

Dim instance As New PIDL(pidl, clone, 
	ownsHandle)
```

**C++**<br />
``` C++
public:
PIDL(
	IntPtr pidl, 
	bool clone = false, 
	bool ownsHandle = true
)
```

**F#**<br />
``` F#
new : 
        pidl : IntPtr * 
        ?clone : bool * 
        ?ownsHandle : bool 
(* Defaults:
        let _clone = defaultArg clone false
        let _ownsHandle = defaultArg ownsHandle true
*)
-> PIDL
```


#### Parameters
&nbsp;<dl><dt>pidl</dt><dd>Type: System.IntPtr<br />A handle to a native ITEMIDLIST.</dd><dt>clone (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), clone the ITEMIDLIST before storing it.</dd><dt>ownsHandle (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), this <a href="T_DevCase_Interop_Unmanaged_PIDL">PIDL</a> instance will release the memory associated with the underlying ITEMIDLIST when done.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_PIDL">PIDL Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_PIDL__ctor">PIDL Overload</a><br /><a href="N_DevCase_Interop_Unmanaged">DevCase.Interop.Unmanaged Namespace</a><br />