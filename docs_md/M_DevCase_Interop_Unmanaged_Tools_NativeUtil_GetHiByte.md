# NativeUtil.GetHiByte Method 
 

Gets the high-order byte of a WORD value.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static byte GetHiByte(
	ushort word
)
```

**VB**<br />
``` VB
Public Shared Function GetHiByte ( 
	word As UShort
) As Byte
```

**VB Usage**<br />
``` VB Usage
Dim word As UShort
Dim returnValue As Byte

returnValue = NativeUtil.GetHiByte(word)
```

**C++**<br />
``` C++
public:
static unsigned char GetHiByte(
	unsigned short word
)
```

**F#**<br />
``` F#
static member GetHiByte : 
        word : uint16 -> byte 

```


#### Parameters
&nbsp;<dl><dt>word</dt><dd>Type: System.UInt16<br />The WORD value that contains the LOBYTE and the HIBYTE.</dd></dl>

#### Return Value
Type: Byte<br />The HIBYTE value.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim value as Byte = GetHiByte(UShort.MaxValue)
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Tools_NativeUtil">NativeUtil Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools Namespace</a><br />