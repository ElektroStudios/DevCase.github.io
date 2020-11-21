# IMMNotificationClient.OnDeviceStateChanged Method 
 

Notifies the client that the default audio endpoint device for a particular role has changed.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult OnDeviceStateChanged(
	string deviceId,
	EDeviceState newState
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function OnDeviceStateChanged ( 
	deviceId As String,
	newState As EDeviceState
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IMMNotificationClient
Dim deviceId As String
Dim newState As EDeviceState
Dim returnValue As HResult

returnValue = instance.OnDeviceStateChanged(deviceId, 
	newState)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult OnDeviceStateChanged(
	String^ deviceId, 
	EDeviceState newState
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract OnDeviceStateChanged : 
        deviceId : string * 
        newState : EDeviceState -> HResult 

```


#### Parameters
&nbsp;<dl><dt>deviceId</dt><dd>Type: System.String<br />The endpoint ID string that identifies the audio endpoint device.</dd><dt>newState</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_EDeviceState">DevCase.Interop.Unmanaged.Win32.Enums.EDeviceState</a><br />The <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_EDeviceState">EDeviceState</a> constant that indicates the new state.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />\[Missing <returns> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IMMNotificationClient.OnDeviceStateChanged(System.String,DevCase.Interop.Unmanaged.Win32.Enums.EDeviceState)"\]

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMNotificationClient">IMMNotificationClient Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />