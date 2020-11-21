# IAudioSessionManager2.RegisterSessionNotification Method 
 

Registers the application to receive a notification when a session is created.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult RegisterSessionNotification(
	IAudioSessionNotification client
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function RegisterSessionNotification ( 
	client As IAudioSessionNotification
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IAudioSessionManager2
Dim client As IAudioSessionNotification
Dim returnValue As HResult

returnValue = instance.RegisterSessionNotification(client)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult RegisterSessionNotification(
	[InAttribute] IAudioSessionNotification^ client
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract RegisterSessionNotification : 
        client : IAudioSessionNotification -> HResult 

```


#### Parameters
&nbsp;<dl><dt>client</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionNotification">DevCase.Interop.Unmanaged.Win32.Interfaces.IAudioSessionNotification</a><br />A pointer to the application's implementation of the <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionNotification">IAudioSessionNotification</a> interface. 

 If the method call succeeds, it calls the AddRef method on the application's <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionNotification">IAudioSessionNotification</a> interface.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionManager2">IAudioSessionManager2 Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />