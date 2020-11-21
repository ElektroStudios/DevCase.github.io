# SnesRom.Version Property 
 

Gets or sets the version number.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia_Gaming">DevCase.Core.Multimedia.Gaming</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public byte Version { get; set; }
```

**VB**<br />
``` VB
Public Property Version As Byte
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As SnesRom
Dim value As Byte

value = instance.Version

instance.Version = value
```

**C++**<br />
``` C++
public:
property unsigned char Version {
	unsigned char get ();
	void set (unsigned char value);
}
```

**F#**<br />
``` F#
member Version : byte with get, set

```


#### Property Value
Type: Byte<br />The version number.

## Remarks
<a href="http://romhack.wikia.com/wiki/SNES_header" target="_blank">http://romhack.wikia.com/wiki/SNES_header</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_Gaming_SnesRom">SnesRom Class</a><br /><a href="N_DevCase_Core_Multimedia_Gaming">DevCase.Core.Multimedia.Gaming Namespace</a><br />