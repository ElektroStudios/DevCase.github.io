# SnesRomCountry.Region Property 
 

Gets the region, which can be PAL or NTSC.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia_Gaming">DevCase.Core.Multimedia.Gaming</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public SnesRegionTypeEnum Region { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property Region As SnesRegionTypeEnum
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As SnesRomCountry
Dim value As SnesRegionTypeEnum

value = instance.Region

```

**C++**<br />
``` C++
public:
property SnesRegionTypeEnum Region {
	SnesRegionTypeEnum get ();
}
```

**F#**<br />
``` F#
member Region : SnesRegionTypeEnum with get

```


#### Property Value
Type: <a href="T_DevCase_Core_Multimedia_Gaming_SnesRegionTypeEnum">SnesRegionTypeEnum</a><br />The country code.

## Remarks
<a href="http://romhack.wikia.com/wiki/SNES_header" target="_blank">http://romhack.wikia.com/wiki/SNES_header</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_Gaming_SnesRomCountry">SnesRomCountry Class</a><br /><a href="N_DevCase_Core_Multimedia_Gaming">DevCase.Core.Multimedia.Gaming Namespace</a><br />