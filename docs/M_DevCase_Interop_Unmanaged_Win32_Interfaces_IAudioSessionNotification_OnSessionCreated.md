# IAudioSessionNotification.OnSessionCreated Method 
 

Notifies the registered processes that the audio session has been created.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult OnSessionCreated(
	IAudioSessionControl newSession
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function OnSessionCreated ( 
	newSession As IAudioSessionControl
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IAudioSessionNotification
Dim newSession As IAudioSessionControl
Dim returnValue As HResult

returnValue = instance.OnSessionCreated(newSession)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult OnSessionCreated(
	IAudioSessionControl^ newSession
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract OnSessionCreated : 
        newSession : IAudioSessionControl -> HResult 

```


#### Parameters
&nbsp;<dl><dt>newSession</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl">DevCase.Interop.Unmanaged.Win32.Interfaces.IAudioSessionControl</a><br />Pointer to the <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl">IAudioSessionControl</a> interface of the audio session that was created.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionNotification">IAudioSessionNotification Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />