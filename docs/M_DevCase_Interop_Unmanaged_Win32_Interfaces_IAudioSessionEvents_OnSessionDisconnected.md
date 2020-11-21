# IAudioSessionEvents.OnSessionDisconnected Method 
 

Notifies the client that the session has been disconnected.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult OnSessionDisconnected(
	EAudioSessionDisconnectReason disconnectReason
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function OnSessionDisconnected ( 
	disconnectReason As EAudioSessionDisconnectReason
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IAudioSessionEvents
Dim disconnectReason As EAudioSessionDisconnectReason
Dim returnValue As HResult

returnValue = instance.OnSessionDisconnected(disconnectReason)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult OnSessionDisconnected(
	[InAttribute] EAudioSessionDisconnectReason disconnectReason
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract OnSessionDisconnected : 
        disconnectReason : EAudioSessionDisconnectReason -> HResult 

```


#### Parameters
&nbsp;<dl><dt>disconnectReason</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_EAudioSessionDisconnectReason">DevCase.Interop.Unmanaged.Win32.Enums.EAudioSessionDisconnectReason</a><br />The reason that the audio session was disconnected.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionEvents">IAudioSessionEvents Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />