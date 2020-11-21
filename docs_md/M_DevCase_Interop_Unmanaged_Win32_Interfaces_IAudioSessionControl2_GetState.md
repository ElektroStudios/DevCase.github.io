# IAudioSessionControl2.GetState Method 
 

Retrieves the current state of the audio session.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult GetState(
	out EAudioSessionState refState
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function GetState ( 
	<OutAttribute> ByRef refState As EAudioSessionState
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IAudioSessionControl2
Dim refState As EAudioSessionState
Dim returnValue As HResult

returnValue = instance.GetState(refState)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult GetState(
	[OutAttribute] EAudioSessionState% refState
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract GetState : 
        refState : EAudioSessionState byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>refState</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_EAudioSessionState">DevCase.Interop.Unmanaged.Win32.Enums.EAudioSessionState</a><br />Receives the current session state.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl2">IAudioSessionControl2 Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />