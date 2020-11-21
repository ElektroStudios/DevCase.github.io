# IMMNotificationClient.OnDeviceAdded Method 
 

Indicates that a new audio endpoint device has been added.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult OnDeviceAdded(
	string deviceId
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function OnDeviceAdded ( 
	deviceId As String
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IMMNotificationClient
Dim deviceId As String
Dim returnValue As HResult

returnValue = instance.OnDeviceAdded(deviceId)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult OnDeviceAdded(
	String^ deviceId
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract OnDeviceAdded : 
        deviceId : string -> HResult 

```


#### Parameters
&nbsp;<dl><dt>deviceId</dt><dd>Type: System.String<br />The endpoint ID string that identifies the audio endpoint device.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />\[Missing <returns> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IMMNotificationClient.OnDeviceAdded(System.String)"\]

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMNotificationClient">IMMNotificationClient Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />