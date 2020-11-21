# NativeUtil.MakeWord Method 
 

Creates a (16-Bit Unsigned Integer) WORD value from a LOBYTE and a HIBYTE.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ushort MakeWord(
	byte loByte,
	byte hiByte
)
```

**VB**<br />
``` VB
Public Shared Function MakeWord ( 
	loByte As Byte,
	hiByte As Byte
) As UShort
```

**VB Usage**<br />
``` VB Usage
Dim loByte As Byte
Dim hiByte As Byte
Dim returnValue As UShort

returnValue = NativeUtil.MakeWord(loByte, 
	hiByte)
```

**C++**<br />
``` C++
public:
static unsigned short MakeWord(
	unsigned char loByte, 
	unsigned char hiByte
)
```

**F#**<br />
``` F#
static member MakeWord : 
        loByte : byte * 
        hiByte : byte -> uint16 

```


#### Parameters
&nbsp;<dl><dt>loByte</dt><dd>Type: System.Byte<br />The low-order byte.</dd><dt>hiByte</dt><dd>Type: System.Byte<br />The high-order byte.</dd></dl>

#### Return Value
Type: UInt16<br />The resulting WORD value.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms632663(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms632663(v=vs.85).aspx</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim value as UShort = MakeWord(Byte.MaxValue, Byte.MaxValue)
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Tools_NativeUtil">NativeUtil Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools Namespace</a><br />