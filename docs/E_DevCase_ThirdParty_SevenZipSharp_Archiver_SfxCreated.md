# Archiver.SfxCreated Event
 

Occurs when a SFX is created.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event Archiver.SfxCreatedEventHandler SfxCreated
```

**VB**<br />
``` VB
Public Event SfxCreated As Archiver.SfxCreatedEventHandler
```

**VB Usage**<br />
``` VB Usage
Dim instance As Archiver
Dim handler As Archiver.SfxCreatedEventHandler

AddHandler instance.SfxCreated, handler

```

**C++**<br />
``` C++
public:
 event Archiver.SfxCreatedEventHandler^ SfxCreated {
	void add (Archiver.SfxCreatedEventHandler^ value);
	void remove (Archiver.SfxCreatedEventHandler^ value);
}
```

**F#**<br />
``` F#
member SfxCreated : IEvent<Archiver.SfxCreatedEventHandler,
    string>

```


#### Value
Type: <a href="T_DevCase_ThirdParty_SevenZipSharp_Archiver_SfxCreatedEventHandler">DevCase.ThirdParty.SevenZipSharp.Archiver.SfxCreatedEventHandler</a>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_SevenZipSharp_Archiver">Archiver Class</a><br /><a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp Namespace</a><br />