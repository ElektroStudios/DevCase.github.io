# ID3v2Tag.Artist Property 
 

Gets or sets the `Artist` metatada field of the audio file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_TagLibSharp">DevCase.ThirdParty.TagLibSharp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public override string Artist { get; set; }
```

**VB**<br />
``` VB
Public Overrides Property Artist As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As ID3v2Tag
Dim value As String

value = instance.Artist

instance.Artist = value
```

**C++**<br />
``` C++
public:
virtual property String^ Artist {
	String^ get () override;
	void set (String^ value) override;
}
```

**F#**<br />
``` F#
abstract Artist : string with get, set
override Artist : string with get, set
```


#### Property Value
Type: String<br />The `Artist` metatada field of the audio file.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_TagLibSharp_ID3v2Tag">ID3v2Tag Class</a><br /><a href="N_DevCase_ThirdParty_TagLibSharp">DevCase.ThirdParty.TagLibSharp Namespace</a><br />