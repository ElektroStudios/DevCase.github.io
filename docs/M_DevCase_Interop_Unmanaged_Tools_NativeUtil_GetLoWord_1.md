# NativeUtil.GetLoWord Method (UInt32)
 

Gets the low-order WORD of a DWORD value.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ushort GetLoWord(
	uint dWord
)
```

**VB**<br />
``` VB
Public Shared Function GetLoWord ( 
	dWord As UInteger
) As UShort
```

**VB Usage**<br />
``` VB Usage
Dim dWord As UInteger
Dim returnValue As UShort

returnValue = NativeUtil.GetLoWord(dWord)
```

**C++**<br />
``` C++
public:
static unsigned short GetLoWord(
	unsigned int dWord
)
```

**F#**<br />
``` F#
static member GetLoWord : 
        dWord : uint32 -> uint16 

```


#### Parameters
&nbsp;<dl><dt>dWord</dt><dd>Type: System.UInt32<br />The DWORD value that contains the LOWORD and the HIWORD.</dd></dl>

#### Return Value
Type: UInt16<br />The low-order WORD value.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim value as UShort = GetLoWord(UInteger.MaxValue)
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Tools_NativeUtil">NativeUtil Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Tools_NativeUtil_GetLoWord">GetLoWord Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools Namespace</a><br />