# VistaCoreAudioApiHelper.GetChannelVolume Method 
 

Gets the volume of an specific device channel.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VistaCoreAudio">DevCase.ThirdParty.VistaCoreAudio</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int GetChannelVolume(
	int channelIndex
)
```

**VB**<br />
``` VB
Public Function GetChannelVolume ( 
	channelIndex As Integer
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As VistaCoreAudioApiHelper
Dim channelIndex As Integer
Dim returnValue As Integer

returnValue = instance.GetChannelVolume(channelIndex)
```

**C++**<br />
``` C++
public:
int GetChannelVolume(
	int channelIndex
)
```

**F#**<br />
``` F#
member GetChannelVolume : 
        channelIndex : int -> int 

```


#### Parameters
&nbsp;<dl><dt>channelIndex</dt><dd>Type: System.Int32<br />\[Missing <param name="channelIndex"/> documentation for "M:DevCase.ThirdParty.VistaCoreAudio.VistaCoreAudioApiHelper.GetChannelVolume(System.Int32)"\]</dd></dl>

#### Return Value
Type: Int32<br />The current volume of the specified device channel.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VistaCoreAudio_VistaCoreAudioApiHelper">VistaCoreAudioApiHelper Class</a><br /><a href="N_DevCase_ThirdParty_VistaCoreAudio">DevCase.ThirdParty.VistaCoreAudio Namespace</a><br />