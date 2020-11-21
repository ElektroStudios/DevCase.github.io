# SnesRom.RamSize Property 
 

Gets or sets the RAM size, in kilobits. 

 If the return value is 0, the ROM has no RAM.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia_Gaming">DevCase.Core.Multimedia.Gaming</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public SnesSramSizeEnum RamSize { get; set; }
```

**VB**<br />
``` VB
Public Property RamSize As SnesSramSizeEnum
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As SnesRom
Dim value As SnesSramSizeEnum

value = instance.RamSize

instance.RamSize = value
```

**C++**<br />
``` C++
public:
property SnesSramSizeEnum RamSize {
	SnesSramSizeEnum get ();
	void set (SnesSramSizeEnum value);
}
```

**F#**<br />
``` F#
member RamSize : SnesSramSizeEnum with get, set

```


#### Property Value
Type: <a href="T_DevCase_Core_Multimedia_Gaming_SnesSramSizeEnum">SnesSramSizeEnum</a><br />The RAM size, in kilobits.

## Remarks
<a href="http://romhack.wikia.com/wiki/SNES_header" target="_blank">http://romhack.wikia.com/wiki/SNES_header</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_Gaming_SnesRom">SnesRom Class</a><br /><a href="N_DevCase_Core_Multimedia_Gaming">DevCase.Core.Multimedia.Gaming Namespace</a><br />