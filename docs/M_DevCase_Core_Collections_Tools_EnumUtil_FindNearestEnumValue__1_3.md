# EnumUtil.FindNearestEnumValue(*T*) Method (UInt16, EnumFindDirection)
 

Gets the nearest value of an Enum.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Collections_Tools">DevCase.Core.Collections.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static T FindNearestEnumValue<T>(
	ushort value,
	EnumFindDirection direction
)

```

**VB**<br />
``` VB
Public Shared Function FindNearestEnumValue(Of T) ( 
	value As UShort,
	direction As EnumFindDirection
) As T
```

**VB Usage**<br />
``` VB Usage
Dim value As UShort
Dim direction As EnumFindDirection
Dim returnValue As T

returnValue = EnumUtil.FindNearestEnumValue(value, 
	direction)
```

**C++**<br />
``` C++
public:
generic<typename T>
static T FindNearestEnumValue(
	unsigned short value, 
	EnumFindDirection direction
)
```

**F#**<br />
``` F#
static member FindNearestEnumValue : 
        value : uint16 * 
        direction : EnumFindDirection -> 'T 

```


#### Parameters
&nbsp;<dl><dt>value</dt><dd>Type: System.UInt16<br />The existing value.</dd><dt>direction</dt><dd>Type: <a href="T_DevCase_Core_Collections_EnumFindDirection">DevCase.Core.Collections.EnumFindDirection</a><br />The find direction of the nearest value.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of Enum.</dd></dl>

#### Return Value
Type: *T*<br />The nearest value in the specified Enum.

## Examples
This is a code example. 
**VB**<br />
``` VB
Enum Bitrate As UShort
    Kbps128 = 128
    Kbps192 = 192
    Kbps256 = 256
    Kbps320 = 320
End Enum

Dim nearestValue As Bitrate = FindNearestEnumValue(Of Bitrate)(192US, EnumFindDirection.GreaterOrEqual)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Collections_Tools_EnumUtil">EnumUtil Class</a><br /><a href="Overload_DevCase_Core_Collections_Tools_EnumUtil_FindNearestEnumValue">FindNearestEnumValue Overload</a><br /><a href="N_DevCase_Core_Collections_Tools">DevCase.Core.Collections.Tools Namespace</a><br />