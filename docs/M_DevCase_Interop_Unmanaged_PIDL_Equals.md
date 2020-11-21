# PIDL.Equals Method (PIDL)
 

Indicates whether the current object is equal to another object of the same type.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged">DevCase.Interop.Unmanaged</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool Equals(
	PIDL other
)
```

**VB**<br />
``` VB
Public Function Equals ( 
	other As PIDL
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As PIDL
Dim other As PIDL
Dim returnValue As Boolean

returnValue = instance.Equals(other)
```

**C++**<br />
``` C++
public:
virtual bool Equals(
	PIDL^ other
) sealed
```

**F#**<br />
``` F#
abstract Equals : 
        other : PIDL -> bool 
override Equals : 
        other : PIDL -> bool 
```


#### Parameters
&nbsp;<dl><dt>other</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_PIDL">DevCase.Interop.Unmanaged.PIDL</a><br />An object to compare with this object.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the current object is equal to the *other* parameter; otherwise, `false` (`False` in Visual Basic).

#### Implements
IEquatable(T).Equals(T)<br />

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_PIDL">PIDL Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_PIDL_Equals">Equals Overload</a><br /><a href="N_DevCase_Interop_Unmanaged">DevCase.Interop.Unmanaged Namespace</a><br />