# IMMNotificationClient.OnDefaultDeviceChanged Method 
 

Notifies the client that the default audio endpoint device for a particular role has changed.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult OnDefaultDeviceChanged(
	EDataFlow dataFlow,
	ERole deviceRole,
	string defaultDeviceId
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function OnDefaultDeviceChanged ( 
	dataFlow As EDataFlow,
	deviceRole As ERole,
	defaultDeviceId As String
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IMMNotificationClient
Dim dataFlow As EDataFlow
Dim deviceRole As ERole
Dim defaultDeviceId As String
Dim returnValue As HResult

returnValue = instance.OnDefaultDeviceChanged(dataFlow, 
	deviceRole, defaultDeviceId)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult OnDefaultDeviceChanged(
	EDataFlow dataFlow, 
	ERole deviceRole, 
	String^ defaultDeviceId
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract OnDefaultDeviceChanged : 
        dataFlow : EDataFlow * 
        deviceRole : ERole * 
        defaultDeviceId : string -> HResult 

```


#### Parameters
&nbsp;<dl><dt>dataFlow</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_EDataFlow">DevCase.Interop.Unmanaged.Win32.Enums.EDataFlow</a><br />The data-flow direction of the endpoint device.</dd><dt>deviceRole</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ERole">DevCase.Interop.Unmanaged.Win32.Enums.ERole</a><br />The device role of the audio endpoint device.</dd><dt>defaultDeviceId</dt><dd>Type: System.String<br />The endpoint ID string that identifies the audio endpoint device.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />\[Missing <returns> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IMMNotificationClient.OnDefaultDeviceChanged(DevCase.Interop.Unmanaged.Win32.Enums.EDataFlow,DevCase.Interop.Unmanaged.Win32.Enums.ERole,System.String)"\]

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMNotificationClient">IMMNotificationClient Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />