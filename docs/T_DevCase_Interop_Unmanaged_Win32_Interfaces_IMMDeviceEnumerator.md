# IMMDeviceEnumerator Interface
 

Provides methods for enumerating multimedia device resources. 

 In the current implementation of the MMDevice API, the only device resources that this interface can enumerate are audio endpoint devices. 

 A client obtains a reference to an IMMDeviceEnumerator interface by calling the CoCreateInstance. 

 The device resources enumerated by the methods in the IMMDeviceEnumerator interface are represented as collections of objects with <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDevice">IMMDevice</a> interfaces. 

 A collection has an IMMDeviceCollection interface. The IMMDeviceEnumerator.EnumAudioEndpoints method creates a device collection.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)]
[GuidAttribute("A95664D2-9614-4F35-A746-DE8DB63617E6")]
public interface IMMDeviceEnumerator
```

**VB**<br />
``` VB
<ComImportAttribute>
<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>
<GuidAttribute("A95664D2-9614-4F35-A746-DE8DB63617E6")>
Public Interface IMMDeviceEnumerator
```

**VB Usage**<br />
``` VB Usage
Dim instance As IMMDeviceEnumerator
```

**C++**<br />
``` C++
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType::InterfaceIsIUnknown)]
[GuidAttribute(L"A95664D2-9614-4F35-A746-DE8DB63617E6")]
public interface class IMMDeviceEnumerator
```

**F#**<br />
``` F#
[<ComImportAttribute>]
[<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>]
[<GuidAttribute("A95664D2-9614-4F35-A746-DE8DB63617E6")>]
type IMMDeviceEnumerator =  interface end
```

The IMMDeviceEnumerator type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDeviceEnumerator_EnumAudioEndpoints">EnumAudioEndpoints</a></td><td>
Generates a collection of audio endpoint devices that meet the specified criteria.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDeviceEnumerator_GetDefaultAudioEndpoint">GetDefaultAudioEndpoint</a></td><td>
Retrieves the default audio endpoint for the specified data-flow direction and role.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDeviceEnumerator_GetDevice">GetDevice</a></td><td>
Retrieves an endpoint device that is specified by an endpoint device-identification string.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDeviceEnumerator_RegisterEndpointNotificationCallback">RegisterEndpointNotificationCallback</a></td><td>
Registers a client's notification callback interface.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDeviceEnumerator_UnregisterEndpointNotificationCallback">UnregisterEndpointNotificationCallback</a></td><td>
Deletes the registration of a notification interface that the client registered in a previous call to the <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDeviceEnumerator_RegisterEndpointNotificationCallback">RegisterEndpointNotificationCallback(IMMNotificationClient)</a> method.</td></tr></table>&nbsp;
<a href="#immdeviceenumerator-interface">Back to Top</a>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/mmdeviceapi/nn-mmdeviceapi-immdeviceenumerator" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/mmdeviceapi/nn-mmdeviceapi-immdeviceenumerator</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />