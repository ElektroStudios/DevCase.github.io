# NativeUtil.MakeDWord Method 
 

Creates a (32-Bit Unsigned Integer) DWORD value from a LOWORD and a HIWORD.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static uint MakeDWord(
	ushort loWord,
	ushort hiWord
)
```

**VB**<br />
``` VB
Public Shared Function MakeDWord ( 
	loWord As UShort,
	hiWord As UShort
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim loWord As UShort
Dim hiWord As UShort
Dim returnValue As UInteger

returnValue = NativeUtil.MakeDWord(loWord, 
	hiWord)
```

**C++**<br />
``` C++
public:
static unsigned int MakeDWord(
	unsigned short loWord, 
	unsigned short hiWord
)
```

**F#**<br />
``` F#
static member MakeDWord : 
        loWord : uint16 * 
        hiWord : uint16 -> uint32 

```


#### Parameters
&nbsp;<dl><dt>loWord</dt><dd>Type: System.UInt16<br />The low-order WORD.</dd><dt>hiWord</dt><dd>Type: System.UInt16<br />The high-order WORD.</dd></dl>

#### Return Value
Type: UInt32<br />The resulting DWORD value.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim value as UInteger = MakeDWord(UShort.MaxValue, UShort.MaxValue)
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Tools_NativeUtil">NativeUtil Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools Namespace</a><br />