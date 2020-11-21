# NativeUtil.SetLoByte Method 
 

Sets the low-order byte of a WORD value.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ushort SetLoByte(
	ushort word,
	byte loByte
)
```

**VB**<br />
``` VB
Public Shared Function SetLoByte ( 
	word As UShort,
	loByte As Byte
) As UShort
```

**VB Usage**<br />
``` VB Usage
Dim word As UShort
Dim loByte As Byte
Dim returnValue As UShort

returnValue = NativeUtil.SetLoByte(word, 
	loByte)
```

**C++**<br />
``` C++
public:
static unsigned short SetLoByte(
	unsigned short word, 
	unsigned char loByte
)
```

**F#**<br />
``` F#
static member SetLoByte : 
        word : uint16 * 
        loByte : byte -> uint16 

```


#### Parameters
&nbsp;<dl><dt>word</dt><dd>Type: System.UInt16<br />The WORD value that contains the LOBYTE and the HIBYTE.</dd><dt>loByte</dt><dd>Type: System.Byte<br />The new LOBYTE value.</dd></dl>

#### Return Value
Type: UInt16<br />The resulting WORD value containing the HIBYTE and the new LOBYTE.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim value as UShort = SetLoByte(Short.MaxValue, Byte.MaxValue)
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Tools_NativeUtil">NativeUtil Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools Namespace</a><br />