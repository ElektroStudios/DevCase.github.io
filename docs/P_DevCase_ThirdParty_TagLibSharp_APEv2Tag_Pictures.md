# APEv2Tag.Pictures Property 
 

Gets or sets the `Pictures` metatada field of the audio file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_TagLibSharp">DevCase.ThirdParty.TagLibSharp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IPicture[] Pictures { get; set; }
```

**VB**<br />
``` VB
Public Property Pictures As IPicture()
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As APEv2Tag
Dim value As IPicture()

value = instance.Pictures

instance.Pictures = value
```

**C++**<br />
``` C++
public:
property array<IPicture^>^ Pictures {
	array<IPicture^>^ get ();
	void set (array<IPicture^>^ value);
}
```

**F#**<br />
``` F#
member Pictures : IPicture[] with get, set

```


#### Property Value
Type: IPicture[]<br />The `Pictures` metatada field of the audio file.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_TagLibSharp_APEv2Tag">APEv2Tag Class</a><br /><a href="N_DevCase_ThirdParty_TagLibSharp">DevCase.ThirdParty.TagLibSharp Namespace</a><br />