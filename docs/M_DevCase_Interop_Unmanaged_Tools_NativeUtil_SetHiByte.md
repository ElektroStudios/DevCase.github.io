# NativeUtil.SetHiByte Method 
 

Sets the high-order byte of an WORD value.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ushort SetHiByte(
	ushort word,
	byte hiByte
)
```

**VB**<br />
``` VB
Public Shared Function SetHiByte ( 
	word As UShort,
	hiByte As Byte
) As UShort
```

**VB Usage**<br />
``` VB Usage
Dim word As UShort
Dim hiByte As Byte
Dim returnValue As UShort

returnValue = NativeUtil.SetHiByte(word, 
	hiByte)
```

**C++**<br />
``` C++
public:
static unsigned short SetHiByte(
	unsigned short word, 
	unsigned char hiByte
)
```

**F#**<br />
``` F#
static member SetHiByte : 
        word : uint16 * 
        hiByte : byte -> uint16 

```


#### Parameters
&nbsp;<dl><dt>word</dt><dd>Type: System.UInt16<br />The WORD value that contains the LOBYTE and the HIBYTE.</dd><dt>hiByte</dt><dd>Type: System.Byte<br />The new HIBYTE value.</dd></dl>

#### Return Value
Type: UInt16<br />The resulting WORD value containing the LOBYTE and the new HIBYTE.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim value as UShort = SetHiByte(Short.MaxValue, Byte.MaxValue)
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Tools_NativeUtil">NativeUtil Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools Namespace</a><br />