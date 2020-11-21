# NativeUtil.SetLoWord Method 
 

Sets the low-order WORD of a DWORD value.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static uint SetLoWord(
	uint dWord,
	ushort loWord
)
```

**VB**<br />
``` VB
Public Shared Function SetLoWord ( 
	dWord As UInteger,
	loWord As UShort
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim dWord As UInteger
Dim loWord As UShort
Dim returnValue As UInteger

returnValue = NativeUtil.SetLoWord(dWord, 
	loWord)
```

**C++**<br />
``` C++
public:
static unsigned int SetLoWord(
	unsigned int dWord, 
	unsigned short loWord
)
```

**F#**<br />
``` F#
static member SetLoWord : 
        dWord : uint32 * 
        loWord : uint16 -> uint32 

```


#### Parameters
&nbsp;<dl><dt>dWord</dt><dd>Type: System.UInt32<br />The DWORD value that contains the LOWORD and the HIWORD.</dd><dt>loWord</dt><dd>Type: System.UInt16<br />The new LOWORD value.</dd></dl>

#### Return Value
Type: UInt32<br />The resulting DWORD value containing the HIWORD and the new LOWORD.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim value as UInteger = SetLoWord(UInteger.MaxValue, UShort.MaxValue)
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Tools_NativeUtil">NativeUtil Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools Namespace</a><br />