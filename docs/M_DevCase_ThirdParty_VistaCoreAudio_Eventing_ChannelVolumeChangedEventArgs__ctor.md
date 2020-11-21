# ChannelVolumeChangedEventArgs Constructor 
 

Initializes a new instance of the <a href="T_DevCase_ThirdParty_VistaCoreAudio_Eventing_ChannelVolumeChangedEventArgs">ChannelVolumeChangedEventArgs</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VistaCoreAudio_Eventing">DevCase.ThirdParty.VistaCoreAudio.Eventing</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ChannelVolumeChangedEventArgs(
	DeviceChannel channel,
	int volume
)
```

**VB**<br />
``` VB
Public Sub New ( 
	channel As DeviceChannel,
	volume As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim channel As DeviceChannel
Dim volume As Integer

Dim instance As New ChannelVolumeChangedEventArgs(channel, 
	volume)
```

**C++**<br />
``` C++
public:
ChannelVolumeChangedEventArgs(
	DeviceChannel channel, 
	int volume
)
```

**F#**<br />
``` F#
new : 
        channel : DeviceChannel * 
        volume : int -> ChannelVolumeChangedEventArgs
```


#### Parameters
&nbsp;<dl><dt>channel</dt><dd>Type: <a href="T_DevCase_ThirdParty_VistaCoreAudio_DeviceChannel">DevCase.ThirdParty.VistaCoreAudio.DeviceChannel</a><br />The channel.</dd><dt>volume</dt><dd>Type: System.Int32<br />The channel volume.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VistaCoreAudio_Eventing_ChannelVolumeChangedEventArgs">ChannelVolumeChangedEventArgs Class</a><br /><a href="N_DevCase_ThirdParty_VistaCoreAudio_Eventing">DevCase.ThirdParty.VistaCoreAudio.Eventing Namespace</a><br />