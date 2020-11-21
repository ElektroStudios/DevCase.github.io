# ID3v2Tag.Bpm Property 
 

Gets or sets the `BPM` metatada field of the audio file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_TagLibSharp">DevCase.ThirdParty.TagLibSharp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int Bpm { get; set; }
```

**VB**<br />
``` VB
Public Property Bpm As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As ID3v2Tag
Dim value As Integer

value = instance.Bpm

instance.Bpm = value
```

**C++**<br />
``` C++
public:
property int Bpm {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
member Bpm : int with get, set

```


#### Property Value
Type: Int32<br />The `BPM` metatada field of the audio file, or `-1` if the field is not set.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_TagLibSharp_ID3v2Tag">ID3v2Tag Class</a><br /><a href="N_DevCase_ThirdParty_TagLibSharp">DevCase.ThirdParty.TagLibSharp Namespace</a><br />