# IEnumIDList.Skip Method 
 

Skips the specified number of elements in the enumeration sequence.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
void Skip(
	uint count
)
```

**VB**<br />
``` VB
Sub Skip ( 
	count As UInteger
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IEnumIDList
Dim count As UInteger

instance.Skip(count)
```

**C++**<br />
``` C++
void Skip(
	unsigned int count
)
```

**F#**<br />
``` F#
abstract Skip : 
        count : uint32 -> unit 

```


#### Parameters
&nbsp;<dl><dt>count</dt><dd>Type: System.UInt32<br />The number of item identifiers to skip.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IEnumIDList">IEnumIDList Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />