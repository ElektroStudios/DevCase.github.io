# SnesRom.Checksum Property 
 

Gets the checksum.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia_Gaming">DevCase.Core.Multimedia.Gaming</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ushort Checksum { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property Checksum As UShort
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As SnesRom
Dim value As UShort

value = instance.Checksum

```

**C++**<br />
``` C++
public:
property unsigned short Checksum {
	unsigned short get ();
}
```

**F#**<br />
``` F#
member Checksum : uint16 with get

```


#### Property Value
Type: UInt16<br />The checksum.

## Remarks
<a href="http://romhack.wikia.com/wiki/SNES_header" target="_blank">http://romhack.wikia.com/wiki/SNES_header</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_Gaming_SnesRom">SnesRom Class</a><br /><a href="N_DevCase_Core_Multimedia_Gaming">DevCase.Core.Multimedia.Gaming Namespace</a><br />