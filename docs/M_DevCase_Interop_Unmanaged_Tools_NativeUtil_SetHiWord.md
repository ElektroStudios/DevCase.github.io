# NativeUtil.SetHiWord Method 
 

Sets the high-order WORD of a DWORD value.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static uint SetHiWord(
	uint dWord,
	ushort hiWord
)
```

**VB**<br />
``` VB
Public Shared Function SetHiWord ( 
	dWord As UInteger,
	hiWord As UShort
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim dWord As UInteger
Dim hiWord As UShort
Dim returnValue As UInteger

returnValue = NativeUtil.SetHiWord(dWord, 
	hiWord)
```

**C++**<br />
``` C++
public:
static unsigned int SetHiWord(
	unsigned int dWord, 
	unsigned short hiWord
)
```

**F#**<br />
``` F#
static member SetHiWord : 
        dWord : uint32 * 
        hiWord : uint16 -> uint32 

```


#### Parameters
&nbsp;<dl><dt>dWord</dt><dd>Type: System.UInt32<br />The DWORD value that contains the LOWORD and the HIWORD.</dd><dt>hiWord</dt><dd>Type: System.UInt16<br />The new HIWORD value.</dd></dl>

#### Return Value
Type: UInt32<br />The resulting DWORD value containing the LOWORD and the new HIWORD.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim value as UInteger = SetHiWord(UInteger.MaxValue, UShort.MaxValue)
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Tools_NativeUtil">NativeUtil Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools Namespace</a><br />