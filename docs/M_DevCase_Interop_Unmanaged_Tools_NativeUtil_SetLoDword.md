# NativeUtil.SetLoDword Method 
 

Sets the low-order DWORD of an DWORDLONG value.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ulong SetLoDword(
	ulong dwordLong,
	uint loDWord
)
```

**VB**<br />
``` VB
Public Shared Function SetLoDword ( 
	dwordLong As ULong,
	loDWord As UInteger
) As ULong
```

**VB Usage**<br />
``` VB Usage
Dim dwordLong As ULong
Dim loDWord As UInteger
Dim returnValue As ULong

returnValue = NativeUtil.SetLoDword(dwordLong, 
	loDWord)
```

**C++**<br />
``` C++
public:
static unsigned long long SetLoDword(
	unsigned long long dwordLong, 
	unsigned int loDWord
)
```

**F#**<br />
``` F#
static member SetLoDword : 
        dwordLong : uint64 * 
        loDWord : uint32 -> uint64 

```


#### Parameters
&nbsp;<dl><dt>dwordLong</dt><dd>Type: System.UInt64<br />The DWORDLONG value that contains the LODWORD and the HIDWORD.</dd><dt>loDWord</dt><dd>Type: System.UInt32<br />The new LODWORD value.</dd></dl>

#### Return Value
Type: UInt64<br />The resulting DWORDLONG value containing the HIDWORD and the new LODWORD.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim value as ULong = SetLoDword(ULong.MaxValue, UInteger.MaxValue)
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Tools_NativeUtil">NativeUtil Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools Namespace</a><br />