# ERole Enumeration
 

Defines constants that indicate the role that the system has assigned to an audio endpoint device. 

 The <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDeviceEnumerator_GetDefaultAudioEndpoint">GetDefaultAudioEndpoint(EDataFlow, ERole, IMMDevice)</a> and IMMNotificationClient.OnDefaultDeviceChanged methods use the constants defined in the ERole enumeration.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum ERole
```

**VB**<br />
``` VB
Public Enumeration ERole
```

**VB Usage**<br />
``` VB Usage
Dim instance As ERole
```

**C++**<br />
``` C++
public enum class ERole
```

**F#**<br />
``` F#
type ERole
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ERole.Console">**Console**</td><td>0</td><td>Games, system notification sounds, and voice commands.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ERole.Multimedia">**Multimedia**</td><td>1</td><td>Music, movies, narration, and live music recording.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ERole.Communications">**Communications**</td><td>2</td><td>Voice communications (talking to another person).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ERole.ERole_enum_count">**ERole_enum_count**</td><td>3</td><td>The number of members in the ERole enumeration (not counting the ERole_enum_count member).</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/mmdeviceapi/ne-mmdeviceapi-__midl___midl_itf_mmdeviceapi_0000_0000_0002" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/mmdeviceapi/ne-mmdeviceapi-__midl___midl_itf_mmdeviceapi_0000_0000_0002</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />