# SnesRom.Layout Property 
 

Gets the ROM layout. 

 The SNES ROM layout describes how the ROM banks appear in a ROM image and in the SNES address space.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia_Gaming">DevCase.Core.Multimedia.Gaming</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public byte Layout { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property Layout As Byte
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As SnesRom
Dim value As Byte

value = instance.Layout

```

**C++**<br />
``` C++
public:
property unsigned char Layout {
	unsigned char get ();
}
```

**F#**<br />
``` F#
member Layout : byte with get

```


#### Property Value
Type: Byte<br />The ROM layout.

## Remarks
<a href="http://romhack.wikia.com/wiki/SNES_ROM_layout" target="_blank">http://romhack.wikia.com/wiki/SNES_ROM_layout</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_Gaming_SnesRom">SnesRom Class</a><br /><a href="N_DevCase_Core_Multimedia_Gaming">DevCase.Core.Multimedia.Gaming Namespace</a><br />