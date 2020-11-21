# IAudioSessionManager.GetAudioSessionControl Method 
 

Retrieves an audio session control.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult GetAudioSessionControl(
	[OptionalAttribute] Guid sessionId,
	uint streamFlags,
	out IAudioSessionControl refSessionControl
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function GetAudioSessionControl ( 
	<OptionalAttribute> sessionId As Guid,
	streamFlags As UInteger,
	<OutAttribute> ByRef refSessionControl As IAudioSessionControl
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IAudioSessionManager
Dim sessionId As Guid
Dim streamFlags As UInteger
Dim refSessionControl As IAudioSessionControl
Dim returnValue As HResult

returnValue = instance.GetAudioSessionControl(sessionId, 
	streamFlags, refSessionControl)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult GetAudioSessionControl(
	[OptionalAttribute] [InAttribute] Guid sessionId, 
	[InAttribute] unsigned int streamFlags, 
	[OutAttribute] IAudioSessionControl^% refSessionControl
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract GetAudioSessionControl : 
        [<OptionalAttribute>] sessionId : Guid * 
        streamFlags : uint32 * 
        refSessionControl : IAudioSessionControl byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>sessionId (Optional)</dt><dd>Type: System.Guid<br />A new or existing session ID.</dd><dt>streamFlags</dt><dd>Type: System.UInt32<br />Audio session flags.</dd><dt>refSessionControl</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl">DevCase.Interop.Unmanaged.Win32.Interfaces.IAudioSessionControl</a><br />Receives an <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl">IAudioSessionControl</a> interface for the audio session.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionManager">IAudioSessionManager Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />