# PIDL.IsParentOf Method 
 

Determines if this instance is a parent or ancestor of the specified <a href="T_DevCase_Interop_Unmanaged_PIDL">PIDL</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged">DevCase.Interop.Unmanaged</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool IsParentOf(
	PIDL childPidl,
	bool immediate = true
)
```

**VB**<br />
``` VB
Public Function IsParentOf ( 
	childPidl As PIDL,
	Optional immediate As Boolean = true
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As PIDL
Dim childPidl As PIDL
Dim immediate As Boolean
Dim returnValue As Boolean

returnValue = instance.IsParentOf(childPidl, 
	immediate)
```

**C++**<br />
``` C++
public:
bool IsParentOf(
	PIDL^ childPidl, 
	bool immediate = true
)
```

**F#**<br />
``` F#
member IsParentOf : 
        childPidl : PIDL * 
        ?immediate : bool 
(* Defaults:
        let _immediate = defaultArg immediate true
*)
-> bool 

```


#### Parameters
&nbsp;<dl><dt>childPidl</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_PIDL">DevCase.Interop.Unmanaged.PIDL</a><br />Child <a href="T_DevCase_Interop_Unmanaged_PIDL">PIDL</a> instance to test.</dd><dt>immediate (Optional)</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), narrows test to immediate children only.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if this instance is a parent or ancestor of the specified <a href="T_DevCase_Interop_Unmanaged_PIDL">PIDL</a>. `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_PIDL">PIDL Class</a><br /><a href="N_DevCase_Interop_Unmanaged">DevCase.Interop.Unmanaged Namespace</a><br />