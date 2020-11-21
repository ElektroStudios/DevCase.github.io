# ID3v2Tag.Track Property 
 

Gets or sets the `Track` metatada field of the audio file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_TagLibSharp">DevCase.ThirdParty.TagLibSharp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public override int Track { get; set; }
```

**VB**<br />
``` VB
Public Overrides Property Track As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As ID3v2Tag
Dim value As Integer

value = instance.Track

instance.Track = value
```

**C++**<br />
``` C++
public:
virtual property int Track {
	int get () override;
	void set (int value) override;
}
```

**F#**<br />
``` F#
abstract Track : int with get, set
override Track : int with get, set
```


#### Property Value
Type: Int32<br />The `Track` metatada field of the audio file, or `-1` if the field is not set.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_TagLibSharp_ID3v2Tag">ID3v2Tag Class</a><br /><a href="N_DevCase_ThirdParty_TagLibSharp">DevCase.ThirdParty.TagLibSharp Namespace</a><br />