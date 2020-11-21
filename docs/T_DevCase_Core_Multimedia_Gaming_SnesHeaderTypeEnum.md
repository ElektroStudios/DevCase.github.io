# SnesHeaderTypeEnum Enumeration
 

Specifies a SNES ROM header type. 

 A headered ROM has SMC header and SNES header. 

 A headerless ROM has no SMC header, but still contains a SNES header. 

 Note that both a LoRom and HiRom images can be headered, or headerless.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia_Gaming">DevCase.Core.Multimedia.Gaming</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum SnesHeaderTypeEnum
```

**VB**<br />
``` VB
Public Enumeration SnesHeaderTypeEnum
```

**VB Usage**<br />
``` VB Usage
Dim instance As SnesHeaderTypeEnum
```

**C++**<br />
``` C++
public enum class SnesHeaderTypeEnum
```

**F#**<br />
``` F#
type SnesHeaderTypeEnum
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Core.Multimedia.Gaming.SnesHeaderTypeEnum.Headered">**Headered**</td><td>0</td><td>A headered SNES ROM. 

 The ROM contains an SMC header, and also contains an SNES header.</td></tr><tr><td /><td target="F:DevCase.Core.Multimedia.Gaming.SnesHeaderTypeEnum.Headerless">**Headerless**</td><td>1</td><td>A headerless SNES ROM. 

 The ROM does not contains an SMC header, but contains an SNES header.</td></tr></table>

## Remarks
<a href="http://romhack.wikia.com/wiki/SNES_header" target="_blank">http://romhack.wikia.com/wiki/SNES_header</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Multimedia_Gaming">DevCase.Core.Multimedia.Gaming Namespace</a><br />