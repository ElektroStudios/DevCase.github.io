# VistaCoreAudioApiHelper.GetAllChannelVolume Method 
 

Gets the volume of all the device channels.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VistaCoreAudio">DevCase.ThirdParty.VistaCoreAudio</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Dictionary<DeviceChannel, int> GetAllChannelVolume()
```

**VB**<br />
``` VB
Public Function GetAllChannelVolume As Dictionary(Of DeviceChannel, Integer)
```

**VB Usage**<br />
``` VB Usage
Dim instance As VistaCoreAudioApiHelper
Dim returnValue As Dictionary(Of DeviceChannel, Integer)

returnValue = instance.GetAllChannelVolume()
```

**C++**<br />
``` C++
public:
Dictionary<DeviceChannel, int>^ GetAllChannelVolume()
```

**F#**<br />
``` F#
member GetAllChannelVolume : unit -> Dictionary<DeviceChannel, int> 

```


#### Return Value
Type: Dictionary(<a href="T_DevCase_ThirdParty_VistaCoreAudio_DeviceChannel">DeviceChannel</a>, Int32)<br />Dictionary(Of DeviceChannel, System.Int32).

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VistaCoreAudio_VistaCoreAudioApiHelper">VistaCoreAudioApiHelper Class</a><br /><a href="N_DevCase_ThirdParty_VistaCoreAudio">DevCase.ThirdParty.VistaCoreAudio Namespace</a><br />