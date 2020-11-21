# IMMNotificationClient Interface
 

Provides notifications when an audio endpoint device is added or removed, when the state or properties of an endpoint device change, or when there is a change in the default role assigned to an endpoint device. 

 Unlike the other interfaces in this section, which are implemented by the MMDevice API system component, an MMDevice API client implements the IMMNotificationClient interface. 

 To receive notifications, the client passes a pointer to its IMMNotificationClient interface instance as a parameter to the <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDeviceEnumerator_RegisterEndpointNotificationCallback">RegisterEndpointNotificationCallback(IMMNotificationClient)</a> method.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)]
[GuidAttribute("7991EEC9-7E89-4D85-8390-6C703CEC60C0")]
public interface IMMNotificationClient
```

**VB**<br />
``` VB
<ComImportAttribute>
<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>
<GuidAttribute("7991EEC9-7E89-4D85-8390-6C703CEC60C0")>
Public Interface IMMNotificationClient
```

**VB Usage**<br />
``` VB Usage
Dim instance As IMMNotificationClient
```

**C++**<br />
``` C++
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType::InterfaceIsIUnknown)]
[GuidAttribute(L"7991EEC9-7E89-4D85-8390-6C703CEC60C0")]
public interface class IMMNotificationClient
```

**F#**<br />
``` F#
[<ComImportAttribute>]
[<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>]
[<GuidAttribute("7991EEC9-7E89-4D85-8390-6C703CEC60C0")>]
type IMMNotificationClient =  interface end
```

The IMMNotificationClient type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMNotificationClient_OnDefaultDeviceChanged">OnDefaultDeviceChanged</a></td><td>
Notifies the client that the default audio endpoint device for a particular role has changed.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMNotificationClient_OnDeviceAdded">OnDeviceAdded</a></td><td>
Indicates that a new audio endpoint device has been added.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMNotificationClient_OnDeviceRemoved">OnDeviceRemoved</a></td><td>
Indicates that an audio endpoint device has been removed.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMNotificationClient_OnDeviceStateChanged">OnDeviceStateChanged</a></td><td>
Notifies the client that the default audio endpoint device for a particular role has changed.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMNotificationClient_OnPropertyValueChanged">OnPropertyValueChanged</a></td><td>
Indicates that the value of a property belonging to an audio endpoint device has changed.</td></tr></table>&nbsp;
<a href="#immnotificationclient-interface">Back to Top</a>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/mmdeviceapi/nn-mmdeviceapi-immnotificationclient" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/mmdeviceapi/nn-mmdeviceapi-immnotificationclient</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />