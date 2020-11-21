# SnesRom.RomSize Property 
 

Gets or sets the ROM size, in megabits.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia_Gaming">DevCase.Core.Multimedia.Gaming</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public SnesRomSizeEnum RomSize { get; set; }
```

**VB**<br />
``` VB
Public Property RomSize As SnesRomSizeEnum
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As SnesRom
Dim value As SnesRomSizeEnum

value = instance.RomSize

instance.RomSize = value
```

**C++**<br />
``` C++
public:
property SnesRomSizeEnum RomSize {
	SnesRomSizeEnum get ();
	void set (SnesRomSizeEnum value);
}
```

**F#**<br />
``` F#
member RomSize : SnesRomSizeEnum with get, set

```


#### Property Value
Type: <a href="T_DevCase_Core_Multimedia_Gaming_SnesRomSizeEnum">SnesRomSizeEnum</a><br />The ROM size, in megabits.

## Remarks
<a href="http://romhack.wikia.com/wiki/SNES_header" target="_blank">http://romhack.wikia.com/wiki/SNES_header</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_Gaming_SnesRom">SnesRom Class</a><br /><a href="N_DevCase_Core_Multimedia_Gaming">DevCase.Core.Multimedia.Gaming Namespace</a><br />