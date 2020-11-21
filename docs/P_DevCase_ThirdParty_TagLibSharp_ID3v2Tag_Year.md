# ID3v2Tag.Year Property 
 

Gets or sets the `Year` metatada field of the audio file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_TagLibSharp">DevCase.ThirdParty.TagLibSharp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public override int Year { get; set; }
```

**VB**<br />
``` VB
Public Overrides Property Year As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As ID3v2Tag
Dim value As Integer

value = instance.Year

instance.Year = value
```

**C++**<br />
``` C++
public:
virtual property int Year {
	int get () override;
	void set (int value) override;
}
```

**F#**<br />
``` F#
abstract Year : int with get, set
override Year : int with get, set
```


#### Property Value
Type: Int32<br />The `Year` metatada field of the audio file, or `-1` if the field is not set.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_TagLibSharp_ID3v2Tag">ID3v2Tag Class</a><br /><a href="N_DevCase_ThirdParty_TagLibSharp">DevCase.ThirdParty.TagLibSharp Namespace</a><br />