# VistaCoreAudioApiHelper.TimerMasterVolumeChangedDetectionInterval Property 
 

Gets or sets the Master-Volume changed detection interval, in milliseconds. This interval is associated with a timer that monitors and reports Master-Volume changes on the device.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VistaCoreAudio">DevCase.ThirdParty.VistaCoreAudio</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int TimerMasterVolumeChangedDetectionInterval { get; set; }
```

**VB**<br />
``` VB
Public Property TimerMasterVolumeChangedDetectionInterval As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As VistaCoreAudioApiHelper
Dim value As Integer

value = instance.TimerMasterVolumeChangedDetectionInterval

instance.TimerMasterVolumeChangedDetectionInterval = value
```

**C++**<br />
``` C++
public:
property int TimerMasterVolumeChangedDetectionInterval {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
member TimerMasterVolumeChangedDetectionInterval : int with get, set

```


#### Property Value
Type: Int32<br />The Master-Volume detection interval, in milliseconds.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VistaCoreAudio_VistaCoreAudioApiHelper">VistaCoreAudioApiHelper Class</a><br /><a href="N_DevCase_ThirdParty_VistaCoreAudio">DevCase.ThirdParty.VistaCoreAudio Namespace</a><br />