# IAudioSessionManager2.RegisterDuckNotification Method 
 

Registers the application with the session manager to receive ducking notifications.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult RegisterDuckNotification(
	string sessionId,
	IAudioVolumeDuckNotification client
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function RegisterDuckNotification ( 
	sessionId As String,
	client As IAudioVolumeDuckNotification
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IAudioSessionManager2
Dim sessionId As String
Dim client As IAudioVolumeDuckNotification
Dim returnValue As HResult

returnValue = instance.RegisterDuckNotification(sessionId, 
	client)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult RegisterDuckNotification(
	[InAttribute] String^ sessionId, 
	[InAttribute] IAudioVolumeDuckNotification^ client
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract RegisterDuckNotification : 
        sessionId : string * 
        client : IAudioVolumeDuckNotification -> HResult 

```


#### Parameters
&nbsp;<dl><dt>sessionId</dt><dd>Type: System.String<br /></dd><dt>client</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioVolumeDuckNotification">DevCase.Interop.Unmanaged.Win32.Interfaces.IAudioVolumeDuckNotification</a><br />Pointer to the application's implementation of the <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioVolumeDuckNotification">IAudioVolumeDuckNotification</a> interface. 

 The implementation is called when ducking events are raised by the audio system and notifications are sent to the registered applications.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionManager2">IAudioSessionManager2 Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />