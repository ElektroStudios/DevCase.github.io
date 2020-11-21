# NativeUtil.GetLoDWord Method 
 

Gets the low-order DWORD of a DWORDLONG value.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static uint GetLoDWord(
	ulong dWordLong
)
```

**VB**<br />
``` VB
Public Shared Function GetLoDWord ( 
	dWordLong As ULong
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim dWordLong As ULong
Dim returnValue As UInteger

returnValue = NativeUtil.GetLoDWord(dWordLong)
```

**C++**<br />
``` C++
public:
static unsigned int GetLoDWord(
	unsigned long long dWordLong
)
```

**F#**<br />
``` F#
static member GetLoDWord : 
        dWordLong : uint64 -> uint32 

```


#### Parameters
&nbsp;<dl><dt>dWordLong</dt><dd>Type: System.UInt64<br />The DWORDLONG value that contains the LODWORD and the HIDWORD.</dd></dl>

#### Return Value
Type: UInt32<br />The low-order DWORD value.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim value as UInteger = GetLoDWord(ULong.MaxValue)
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Tools_NativeUtil">NativeUtil Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools Namespace</a><br />