# APEv2Tag.Track Property 
 

Gets or sets the `Track` metatada field of the audio file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_TagLibSharp">DevCase.ThirdParty.TagLibSharp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int Track { get; set; }
```

**VB**<br />
``` VB
Public Property Track As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As APEv2Tag
Dim value As Integer

value = instance.Track

instance.Track = value
```

**C++**<br />
``` C++
public:
property int Track {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
member Track : int with get, set

```


#### Property Value
Type: Int32<br />The `Track` metatada field of the audio file, or `-1` if the field is not set.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_TagLibSharp_APEv2Tag">APEv2Tag Class</a><br /><a href="N_DevCase_ThirdParty_TagLibSharp">DevCase.ThirdParty.TagLibSharp Namespace</a><br />