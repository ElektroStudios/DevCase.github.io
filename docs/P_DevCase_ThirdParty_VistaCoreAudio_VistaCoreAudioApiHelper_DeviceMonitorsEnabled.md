# VistaCoreAudioApiHelper.DeviceMonitorsEnabled Property 
 

Gets or sets a value indicating whether the audio device timers that monitors and reports changes are enabled.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VistaCoreAudio">DevCase.ThirdParty.VistaCoreAudio</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool DeviceMonitorsEnabled { get; set; }
```

**VB**<br />
``` VB
Public Property DeviceMonitorsEnabled As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As VistaCoreAudioApiHelper
Dim value As Boolean

value = instance.DeviceMonitorsEnabled

instance.DeviceMonitorsEnabled = value
```

**C++**<br />
``` C++
public:
property bool DeviceMonitorsEnabled {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
member DeviceMonitorsEnabled : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the audio device monitor is enabled; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VistaCoreAudio_VistaCoreAudioApiHelper">VistaCoreAudioApiHelper Class</a><br /><a href="N_DevCase_ThirdParty_VistaCoreAudio">DevCase.ThirdParty.VistaCoreAudio Namespace</a><br />