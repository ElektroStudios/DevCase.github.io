# PIDL.Combine Method 
 

Combines the specified <a href="T_DevCase_Interop_Unmanaged_PIDL">PIDL</a> instances to create a new one.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged">DevCase.Interop.Unmanaged</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static PIDL Combine(
	PIDL first,
	PIDL second
)
```

**VB**<br />
``` VB
Public Shared Function Combine ( 
	first As PIDL,
	second As PIDL
) As PIDL
```

**VB Usage**<br />
``` VB Usage
Dim first As PIDL
Dim second As PIDL
Dim returnValue As PIDL

returnValue = PIDL.Combine(first, 
	second)
```

**C++**<br />
``` C++
public:
static PIDL^ Combine(
	PIDL^ first, 
	PIDL^ second
)
```

**F#**<br />
``` F#
static member Combine : 
        first : PIDL * 
        second : PIDL -> PIDL 

```


#### Parameters
&nbsp;<dl><dt>first</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_PIDL">DevCase.Interop.Unmanaged.PIDL</a><br />The first <a href="T_DevCase_Interop_Unmanaged_PIDL">PIDL</a>.</dd><dt>second</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_PIDL">DevCase.Interop.Unmanaged.PIDL</a><br />The second <a href="T_DevCase_Interop_Unmanaged_PIDL">PIDL</a>.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_PIDL">PIDL</a><br />A managed <a href="T_DevCase_Interop_Unmanaged_PIDL">PIDL</a> instance that contains both supplied lists in their respective order.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_PIDL">PIDL Class</a><br /><a href="N_DevCase_Interop_Unmanaged">DevCase.Interop.Unmanaged Namespace</a><br />