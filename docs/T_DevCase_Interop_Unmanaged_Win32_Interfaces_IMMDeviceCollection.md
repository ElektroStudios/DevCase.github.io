# IMMDeviceCollection Interface
 

Represents a collection of multimedia device resources. 

 In the current implementation, the only device resources that the MMDevice API can create collections of are audio endpoint devices.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)]
[GuidAttribute("0BD7A1BE-7A1A-44DB-8397-CC5392387B5E")]
public interface IMMDeviceCollection
```

**VB**<br />
``` VB
<ComImportAttribute>
<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>
<GuidAttribute("0BD7A1BE-7A1A-44DB-8397-CC5392387B5E")>
Public Interface IMMDeviceCollection
```

**VB Usage**<br />
``` VB Usage
Dim instance As IMMDeviceCollection
```

**C++**<br />
``` C++
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType::InterfaceIsIUnknown)]
[GuidAttribute(L"0BD7A1BE-7A1A-44DB-8397-CC5392387B5E")]
public interface class IMMDeviceCollection
```

**F#**<br />
``` F#
[<ComImportAttribute>]
[<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>]
[<GuidAttribute("0BD7A1BE-7A1A-44DB-8397-CC5392387B5E")>]
type IMMDeviceCollection =  interface end
```

The IMMDeviceCollection type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDeviceCollection_GetCount">GetCount</a></td><td>
retrieves a count of the devices in the device collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDeviceCollection_Item">Item</a></td><td>
Retrieves a pointer to the specified item in the device collection.</td></tr></table>&nbsp;
<a href="#immdevicecollection-interface">Back to Top</a>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/mmdeviceapi/nn-mmdeviceapi-immdevicecollection" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/mmdeviceapi/nn-mmdeviceapi-immdevicecollection</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />