# IAudioSessionControl2.UnregisterAudioSessionNotification Method 
 

Deletes a previous registration by the client to receive notifications.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult UnregisterAudioSessionNotification(
	IAudioSessionEvents client
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function UnregisterAudioSessionNotification ( 
	client As IAudioSessionEvents
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IAudioSessionControl2
Dim client As IAudioSessionEvents
Dim returnValue As HResult

returnValue = instance.UnregisterAudioSessionNotification(client)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult UnregisterAudioSessionNotification(
	[InAttribute] IAudioSessionEvents^ client
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract UnregisterAudioSessionNotification : 
        client : IAudioSessionEvents -> HResult 

```


#### Parameters
&nbsp;<dl><dt>client</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionEvents">DevCase.Interop.Unmanaged.Win32.Interfaces.IAudioSessionEvents</a><br />A client-implemented <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionEvents">IAudioSessionEvents</a> interface.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl2">IAudioSessionControl2 Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />