# EDataFlow Enumeration
 

Defines constants that indicate the direction in which audio data flows between an audio endpoint device and an application. 

 The <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDeviceEnumerator_GetDefaultAudioEndpoint">GetDefaultAudioEndpoint(EDataFlow, ERole, IMMDevice)</a>, IMMDeviceEnumerator.EnumAudioEndpoints, IMMEndpoint.GetDataFlow, and IMMNotificationClient.OnDefaultDeviceChanged methods use the constants defined in the EDataFlow enumeration.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum EDataFlow
```

**VB**<br />
``` VB
Public Enumeration EDataFlow
```

**VB Usage**<br />
``` VB Usage
Dim instance As EDataFlow
```

**C++**<br />
``` C++
public enum class EDataFlow
```

**F#**<br />
``` F#
type EDataFlow
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EDataFlow.Render">**Render**</td><td>0</td><td>Audio rendering stream. 

 Audio data flows from the application to the audio endpoint device, which renders the stream.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EDataFlow.Capture">**Capture**</td><td>1</td><td>Audio capture stream. 

 Audio data flows from the audio endpoint device that captures the stream, to the application.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EDataFlow.All">**All**</td><td>2</td><td>Audio rendering or capture stream. 

 Audio data can flow either from the application to the audio endpoint device, or from the audio endpoint device to the application.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EDataFlow.EDataFlow_enum_count">**EDataFlow_enum_count**</td><td>3</td><td>The number of members in the EDataFlow enumeration (not counting the EDataFlow_enum_count member).</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/mmdeviceapi/ne-mmdeviceapi-__midl___midl_itf_mmdeviceapi_0000_0000_0001" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/mmdeviceapi/ne-mmdeviceapi-__midl___midl_itf_mmdeviceapi_0000_0000_0001</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />