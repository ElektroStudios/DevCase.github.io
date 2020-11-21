# MP3GainExitedEventArgs.GainLevel Property 
 

Gets the volume gain level change applied to file, in decibels. 

 This value is always `0` if performing a <a href="T_DevCase_ThirdParty_MP3Gain_MP3GainOperation">CheckTagInfo</a> task.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MP3Gain_Eventing">DevCase.ThirdParty.MP3Gain.Eventing</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int GainLevel { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property GainLevel As Integer
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As MP3GainExitedEventArgs
Dim value As Integer

value = instance.GainLevel

```

**C++**<br />
``` C++
public:
property int GainLevel {
	int get ();
}
```

**F#**<br />
``` F#
member GainLevel : int with get

```


#### Property Value
Type: Int32<br />\[Missing <value> documentation for "P:DevCase.ThirdParty.MP3Gain.Eventing.MP3GainExitedEventArgs.GainLevel"\]

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MP3Gain_Eventing_MP3GainExitedEventArgs">MP3GainExitedEventArgs Class</a><br /><a href="N_DevCase_ThirdParty_MP3Gain_Eventing">DevCase.ThirdParty.MP3Gain.Eventing Namespace</a><br />