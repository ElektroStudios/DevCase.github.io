# NativeUtil.MakeDWordLong Method 
 

Creates a (64-Bit Unsigned Integer) DWORDLONG value from a LODWORD and a HIDWORD.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ulong MakeDWordLong(
	uint loDWord,
	uint hiDWord
)
```

**VB**<br />
``` VB
Public Shared Function MakeDWordLong ( 
	loDWord As UInteger,
	hiDWord As UInteger
) As ULong
```

**VB Usage**<br />
``` VB Usage
Dim loDWord As UInteger
Dim hiDWord As UInteger
Dim returnValue As ULong

returnValue = NativeUtil.MakeDWordLong(loDWord, 
	hiDWord)
```

**C++**<br />
``` C++
public:
static unsigned long long MakeDWordLong(
	unsigned int loDWord, 
	unsigned int hiDWord
)
```

**F#**<br />
``` F#
static member MakeDWordLong : 
        loDWord : uint32 * 
        hiDWord : uint32 -> uint64 

```


#### Parameters
&nbsp;<dl><dt>loDWord</dt><dd>Type: System.UInt32<br />The low-order DWORD.</dd><dt>hiDWord</dt><dd>Type: System.UInt32<br />The high-order DWORD.</dd></dl>

#### Return Value
Type: UInt64<br />The resulting DWORDLONG value.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim value as ULong = MakeDWordLong(UInteger.MaxValue, UInteger.MaxValue)
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Tools_NativeUtil">NativeUtil Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools Namespace</a><br />