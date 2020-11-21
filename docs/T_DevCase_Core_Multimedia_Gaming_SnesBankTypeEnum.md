# SnesBankTypeEnum Enumeration
 

Specifies a SNES ROM bank type.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia_Gaming">DevCase.Core.Multimedia.Gaming</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum SnesBankTypeEnum
```

**VB**<br />
``` VB
Public Enumeration SnesBankTypeEnum
```

**VB Usage**<br />
``` VB Usage
Dim instance As SnesBankTypeEnum
```

**C++**<br />
``` C++
public enum class SnesBankTypeEnum
```

**F#**<br />
``` F#
type SnesBankTypeEnum
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Core.Multimedia.Gaming.SnesBankTypeEnum.LoRom">**LoRom**</td><td>32704</td><td>A LoROM maps each ROM bank into the upper half (being addresses `$8000` to `$ffff`) of each SNES bank, starting with SNES bank `$00`, and starting again with SNES bank `$80`.</td></tr><tr><td /><td target="F:DevCase.Core.Multimedia.Gaming.SnesBankTypeEnum.HiRom">**HiRom**</td><td>65472</td><td>A HiROM maps each ROM bank into the whole (being addresses `$0000` to `$ffff`) of each SNES bank, starting with SNES bank `$40`, and starting again with SNES bank `$80`.</td></tr></table>

## Remarks
<a href="http://romhack.wikia.com/wiki/SNES_ROM_layout" target="_blank">http://romhack.wikia.com/wiki/SNES_ROM_layout</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Multimedia_Gaming">DevCase.Core.Multimedia.Gaming Namespace</a><br />