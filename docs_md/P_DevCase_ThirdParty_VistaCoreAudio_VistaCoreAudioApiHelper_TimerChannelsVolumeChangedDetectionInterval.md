# VistaCoreAudioApiHelper.TimerChannelsVolumeChangedDetectionInterval Property 
 

Gets or sets the Channels-Volume changed detection interval, in milliseconds. This interval is associated with a timer that monitors and reports Channels-Volume changes on the device.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VistaCoreAudio">DevCase.ThirdParty.VistaCoreAudio</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int TimerChannelsVolumeChangedDetectionInterval { get; set; }
```

**VB**<br />
``` VB
Public Property TimerChannelsVolumeChangedDetectionInterval As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As VistaCoreAudioApiHelper
Dim value As Integer

value = instance.TimerChannelsVolumeChangedDetectionInterval

instance.TimerChannelsVolumeChangedDetectionInterval = value
```

**C++**<br />
``` C++
public:
property int TimerChannelsVolumeChangedDetectionInterval {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
member TimerChannelsVolumeChangedDetectionInterval : int with get, set

```


#### Property Value
Type: Int32<br />The Channels-Volume detection interval, in milliseconds.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VistaCoreAudio_VistaCoreAudioApiHelper">VistaCoreAudioApiHelper Class</a><br /><a href="N_DevCase_ThirdParty_VistaCoreAudio">DevCase.ThirdParty.VistaCoreAudio Namespace</a><br />