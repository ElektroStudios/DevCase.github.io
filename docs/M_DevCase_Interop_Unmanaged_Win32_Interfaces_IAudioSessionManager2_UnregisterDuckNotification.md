# IAudioSessionManager2.UnregisterDuckNotification Method 
 

Deletes a previous registration by the application to receive notifications.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult UnregisterDuckNotification(
	IAudioVolumeDuckNotification client
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function UnregisterDuckNotification ( 
	client As IAudioVolumeDuckNotification
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IAudioSessionManager2
Dim client As IAudioVolumeDuckNotification
Dim returnValue As HResult

returnValue = instance.UnregisterDuckNotification(client)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult UnregisterDuckNotification(
	[InAttribute] IAudioVolumeDuckNotification^ client
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract UnregisterDuckNotification : 
        client : IAudioVolumeDuckNotification -> HResult 

```


#### Parameters
&nbsp;<dl><dt>client</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioVolumeDuckNotification">DevCase.Interop.Unmanaged.Win32.Interfaces.IAudioVolumeDuckNotification</a><br />Pointer to the <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioVolumeDuckNotification">IAudioVolumeDuckNotification</a> interface that is implemented by the application. 

 Pass the same interface pointer that was specified to the session manager in a previous call to the <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionManager2_RegisterDuckNotification">RegisterDuckNotification(String, IAudioVolumeDuckNotification)</a> method. 

 If the UnregisterDuckNotification(IAudioVolumeDuckNotification) method succeeds, it calls the Release method on the application's <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioVolumeDuckNotification">IAudioVolumeDuckNotification</a> interface.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionManager2">IAudioSessionManager2 Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />