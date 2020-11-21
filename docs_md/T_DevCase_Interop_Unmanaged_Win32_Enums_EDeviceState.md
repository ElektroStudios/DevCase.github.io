# EDeviceState Enumeration
 

Indicate the current state of an audio endpoint device. 

 The <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDevice_GetState">GetState(EDeviceState)</a> function use the constants defined in the EDeviceState enumeration.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum EDeviceState
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration EDeviceState
```

**VB Usage**<br />
``` VB Usage
Dim instance As EDeviceState
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class EDeviceState
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type EDeviceState
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EDeviceState.Active">**Active**</td><td>1</td><td>The audio endpoint device is active. 

 That is, the audio adapter that connects to the endpoint device is present and enabled. 

 In addition, if the endpoint device plugs into a jack on the adapter, then the endpoint device is plugged in.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EDeviceState.Disabled">**Disabled**</td><td>2</td><td>The audio endpoint device is disabled. 

 The user has disabled the device in the Windows multimedia control panel, Mmsys.cpl.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EDeviceState.NotPresent">**NotPresent**</td><td>4</td><td>The audio endpoint device is not present because the audio adapter that connects to the endpoint device has been removed from the system, or the user has disabled the adapter device in Device Manager.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EDeviceState.Unplugged">**Unplugged**</td><td>8</td><td>The audio endpoint device is unplugged. 

 The audio adapter that contains the jack for the endpoint device is present and enabled, but the endpoint device is not plugged into the jack. 

 Only a device with jack-presence detection can be in this state.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EDeviceState.All">**All**</td><td>15</td><td>Includes audio endpoint devices in all states active, disabled, not present, and unplugged.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/CoreAudio/device-state-xxx-constants" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/CoreAudio/device-state-xxx-constants</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />