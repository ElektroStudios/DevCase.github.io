# IAudioSessionManager2.UnregisterSessionNotification Method 
 

Deletes the registration to receive a notification when a session is created.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult UnregisterSessionNotification(
	IAudioSessionNotification client
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function UnregisterSessionNotification ( 
	client As IAudioSessionNotification
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IAudioSessionManager2
Dim client As IAudioSessionNotification
Dim returnValue As HResult

returnValue = instance.UnregisterSessionNotification(client)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult UnregisterSessionNotification(
	[InAttribute] IAudioSessionNotification^ client
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract UnregisterSessionNotification : 
        client : IAudioSessionNotification -> HResult 

```


#### Parameters
&nbsp;<dl><dt>client</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionNotification">DevCase.Interop.Unmanaged.Win32.Interfaces.IAudioSessionNotification</a><br />A pointer to the application's implementation of the <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionNotification">IAudioSessionNotification</a> interface. 

 Pass the same interface pointer that was specified to the session manager in a previous call to <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionManager2_RegisterSessionNotification">RegisterSessionNotification(IAudioSessionNotification)</a> to register for notification. 

 If the UnregisterSessionNotification(IAudioSessionNotification) method succeeds, it calls the Release method on the application's <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionNotification">IAudioSessionNotification</a> interface.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionManager2">IAudioSessionManager2 Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />