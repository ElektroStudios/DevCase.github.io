# NativeUtil.SetHiDword Method 
 

Sets the high-order DWORD of a DWORDLONG value.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ulong SetHiDword(
	ulong dWordLong,
	uint hiDWord
)
```

**VB**<br />
``` VB
Public Shared Function SetHiDword ( 
	dWordLong As ULong,
	hiDWord As UInteger
) As ULong
```

**VB Usage**<br />
``` VB Usage
Dim dWordLong As ULong
Dim hiDWord As UInteger
Dim returnValue As ULong

returnValue = NativeUtil.SetHiDword(dWordLong, 
	hiDWord)
```

**C++**<br />
``` C++
public:
static unsigned long long SetHiDword(
	unsigned long long dWordLong, 
	unsigned int hiDWord
)
```

**F#**<br />
``` F#
static member SetHiDword : 
        dWordLong : uint64 * 
        hiDWord : uint32 -> uint64 

```


#### Parameters
&nbsp;<dl><dt>dWordLong</dt><dd>Type: System.UInt64<br />\[Missing <param name="dWordLong"/> documentation for "M:DevCase.Interop.Unmanaged.Tools.NativeUtil.SetHiDword(System.UInt64,System.UInt32)"\]</dd><dt>hiDWord</dt><dd>Type: System.UInt32<br />The new HIDWORD value.</dd></dl>

#### Return Value
Type: UInt64<br />The resulting DWORDLONG value containing the LODWORD and the new HIDWORD.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim value as ULong = SetHiDword(ULong.MaxValue, UInteger.MaxValue)
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Tools_NativeUtil">NativeUtil Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools Namespace</a><br />