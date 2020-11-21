# MP3GainWrapper.ApplyChannelGain Method (String, MP3GainChannel, Int32, Boolean)
 

Applies a volume gain change on the specified audio file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MP3Gain">DevCase.ThirdParty.MP3Gain</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int ApplyChannelGain(
	string filepath,
	MP3GainChannel channel,
	int gainLevel,
	bool preserveDatestamp = true
)
```

**VB**<br />
``` VB
Public Function ApplyChannelGain ( 
	filepath As String,
	channel As MP3GainChannel,
	gainLevel As Integer,
	Optional preserveDatestamp As Boolean = true
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As MP3GainWrapper
Dim filepath As String
Dim channel As MP3GainChannel
Dim gainLevel As Integer
Dim preserveDatestamp As Boolean
Dim returnValue As Integer

returnValue = instance.ApplyChannelGain(filepath, 
	channel, gainLevel, preserveDatestamp)
```

**C++**<br />
``` C++
public:
int ApplyChannelGain(
	String^ filepath, 
	MP3GainChannel channel, 
	int gainLevel, 
	bool preserveDatestamp = true
)
```

**F#**<br />
``` F#
member ApplyChannelGain : 
        filepath : string * 
        channel : MP3GainChannel * 
        gainLevel : int * 
        ?preserveDatestamp : bool 
(* Defaults:
        let _preserveDatestamp = defaultArg preserveDatestamp true
*)
-> int 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The audio filepath.</dd><dt>channel</dt><dd>Type: <a href="T_DevCase_ThirdParty_MP3Gain_MP3GainChannel">DevCase.ThirdParty.MP3Gain.MP3GainChannel</a><br />The stereo channel for which to apply the gain change.</dd><dt>gainLevel</dt><dd>Type: System.Int32<br />The volume gain change, in decibels.</dd><dt>preserveDatestamp (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), the file date is untouched after successful task.</dd></dl>

#### Return Value
Type: Int32<br />The process exit code.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td>gainLevel;Value from range -100 to +100 is required.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MP3Gain_MP3GainWrapper">MP3GainWrapper Class</a><br /><a href="Overload_DevCase_ThirdParty_MP3Gain_MP3GainWrapper_ApplyChannelGain">ApplyChannelGain Overload</a><br /><a href="N_DevCase_ThirdParty_MP3Gain">DevCase.ThirdParty.MP3Gain Namespace</a><br />