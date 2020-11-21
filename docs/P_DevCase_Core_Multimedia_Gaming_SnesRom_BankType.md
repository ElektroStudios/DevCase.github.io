# SnesRom.BankType Property 
 

Gets the bank type. 

 An image contains only LoROM banks or only HiROM banks, not both.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia_Gaming">DevCase.Core.Multimedia.Gaming</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public SnesBankTypeEnum BankType { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property BankType As SnesBankTypeEnum
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As SnesRom
Dim value As SnesBankTypeEnum

value = instance.BankType

```

**C++**<br />
``` C++
public:
property SnesBankTypeEnum BankType {
	SnesBankTypeEnum get ();
}
```

**F#**<br />
``` F#
member BankType : SnesBankTypeEnum with get

```


#### Property Value
Type: <a href="T_DevCase_Core_Multimedia_Gaming_SnesBankTypeEnum">SnesBankTypeEnum</a><br />The bank type.

## Remarks
<a href="http://romhack.wikia.com/wiki/SNES_ROM_layout" target="_blank">http://romhack.wikia.com/wiki/SNES_ROM_layout</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_Gaming_SnesRom">SnesRom Class</a><br /><a href="N_DevCase_Core_Multimedia_Gaming">DevCase.Core.Multimedia.Gaming Namespace</a><br />