# IMMDeviceEnumerator.UnregisterEndpointNotificationCallback Method 
 

Deletes the registration of a notification interface that the client registered in a previous call to the <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDeviceEnumerator_RegisterEndpointNotificationCallback">RegisterEndpointNotificationCallback(IMMNotificationClient)</a> method.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult UnregisterEndpointNotificationCallback(
	IMMNotificationClient client
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function UnregisterEndpointNotificationCallback ( 
	client As IMMNotificationClient
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IMMDeviceEnumerator
Dim client As IMMNotificationClient
Dim returnValue As HResult

returnValue = instance.UnregisterEndpointNotificationCallback(client)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult UnregisterEndpointNotificationCallback(
	[InAttribute] IMMNotificationClient^ client
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract UnregisterEndpointNotificationCallback : 
        client : IMMNotificationClient -> HResult 

```


#### Parameters
&nbsp;<dl><dt>client</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMNotificationClient">DevCase.Interop.Unmanaged.Win32.Interfaces.IMMNotificationClient</a><br />A <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMNotificationClient">IMMNotificationClient</a> interface that was previously registered for notification callbacks.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDeviceEnumerator">IMMDeviceEnumerator Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />