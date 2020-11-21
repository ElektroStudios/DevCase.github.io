# SnesRom.CartridgeType Property 
 

Gets the cartrifge type, it can be a ROM only, or a ROM with save-RAM.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia_Gaming">DevCase.Core.Multimedia.Gaming</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public SnesCartridgeTypeEnum CartridgeType { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property CartridgeType As SnesCartridgeTypeEnum
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As SnesRom
Dim value As SnesCartridgeTypeEnum

value = instance.CartridgeType

```

**C++**<br />
``` C++
public:
property SnesCartridgeTypeEnum CartridgeType {
	SnesCartridgeTypeEnum get ();
}
```

**F#**<br />
``` F#
member CartridgeType : SnesCartridgeTypeEnum with get

```


#### Property Value
Type: <a href="T_DevCase_Core_Multimedia_Gaming_SnesCartridgeTypeEnum">SnesCartridgeTypeEnum</a><br />The cartridge type.

## Remarks
<a href="http://romhack.wikia.com/wiki/SNES_header" target="_blank">http://romhack.wikia.com/wiki/SNES_header</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_Gaming_SnesRom">SnesRom Class</a><br /><a href="N_DevCase_Core_Multimedia_Gaming">DevCase.Core.Multimedia.Gaming Namespace</a><br />