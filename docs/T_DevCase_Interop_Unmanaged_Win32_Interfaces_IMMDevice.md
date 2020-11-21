# IMMDevice Interface
 

Provides methods for enumerating multimedia device resources. 

 In the current implementation of the MMDevice API, the only device resources that this interface can enumerate are audio endpoint devices. 

 A client obtains a reference to an <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDeviceEnumerator">IMMDeviceEnumerator</a> interface by calling the CoCreateInstance. 

 The device resources enumerated by the methods in the IMMDeviceEnumerator interface are represented as collections of objects with IMMDevice interfaces. 

 A collection has an IMMDeviceCollection interface. The IMMDeviceEnumerator.EnumAudioEndpoints method creates a device collection.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)]
[GuidAttribute("D666063F-1587-4E43-81F1-B948E807363F")]
public interface IMMDevice
```

**VB**<br />
``` VB
<ComImportAttribute>
<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>
<GuidAttribute("D666063F-1587-4E43-81F1-B948E807363F")>
Public Interface IMMDevice
```

**VB Usage**<br />
``` VB Usage
Dim instance As IMMDevice
```

**C++**<br />
``` C++
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType::InterfaceIsIUnknown)]
[GuidAttribute(L"D666063F-1587-4E43-81F1-B948E807363F")]
public interface class IMMDevice
```

**F#**<br />
``` F#
[<ComImportAttribute>]
[<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>]
[<GuidAttribute("D666063F-1587-4E43-81F1-B948E807363F")>]
type IMMDevice =  interface end
```

The IMMDevice type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDevice_Activate">Activate</a></td><td>
Creates a COM object with the specified interface</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDevice_GetId">GetId</a></td><td>
Retrieves an endpoint ID string that identifies the audio endpoint device</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDevice_GetState">GetState</a></td><td>
Retrieves the current device state.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDevice_OpenPropertyStore">OpenPropertyStore</a></td><td>
Retrieves an interface to the device's property store.</td></tr></table>&nbsp;
<a href="#immdevice-interface">Back to Top</a>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/mmdeviceapi/nn-mmdeviceapi-immdevice" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/mmdeviceapi/nn-mmdeviceapi-immdevice</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />