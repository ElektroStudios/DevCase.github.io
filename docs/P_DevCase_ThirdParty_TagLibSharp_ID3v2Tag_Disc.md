# ID3v2Tag.Disc Property 
 

Gets or sets the `Disc` metatada field of the audio file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_TagLibSharp">DevCase.ThirdParty.TagLibSharp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int Disc { get; set; }
```

**VB**<br />
``` VB
Public Property Disc As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As ID3v2Tag
Dim value As Integer

value = instance.Disc

instance.Disc = value
```

**C++**<br />
``` C++
public:
property int Disc {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
member Disc : int with get, set

```


#### Property Value
Type: Int32<br />The `Disc` metatada field of the audio file, or `-1` if the field is not set.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_TagLibSharp_ID3v2Tag">ID3v2Tag Class</a><br /><a href="N_DevCase_ThirdParty_TagLibSharp">DevCase.ThirdParty.TagLibSharp Namespace</a><br />