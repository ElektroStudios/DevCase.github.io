# IAudioSessionManager.GetSimpleAudioVolume Method 
 

Retrieves a simple audio volume control.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult GetSimpleAudioVolume(
	[OptionalAttribute] Guid sessionId,
	uint streamFlags,
	out ISimpleAudioVolume refAudioVolume
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function GetSimpleAudioVolume ( 
	<OptionalAttribute> sessionId As Guid,
	streamFlags As UInteger,
	<OutAttribute> ByRef refAudioVolume As ISimpleAudioVolume
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IAudioSessionManager
Dim sessionId As Guid
Dim streamFlags As UInteger
Dim refAudioVolume As ISimpleAudioVolume
Dim returnValue As HResult

returnValue = instance.GetSimpleAudioVolume(sessionId, 
	streamFlags, refAudioVolume)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult GetSimpleAudioVolume(
	[OptionalAttribute] [InAttribute] Guid sessionId, 
	[InAttribute] unsigned int streamFlags, 
	[OutAttribute] ISimpleAudioVolume^% refAudioVolume
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract GetSimpleAudioVolume : 
        [<OptionalAttribute>] sessionId : Guid * 
        streamFlags : uint32 * 
        refAudioVolume : ISimpleAudioVolume byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>sessionId (Optional)</dt><dd>Type: System.Guid<br />A new or existing session ID.</dd><dt>streamFlags</dt><dd>Type: System.UInt32<br />Audio session flags.</dd><dt>refAudioVolume</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ISimpleAudioVolume">DevCase.Interop.Unmanaged.Win32.Interfaces.ISimpleAudioVolume</a><br />Receives an <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ISimpleAudioVolume">ISimpleAudioVolume</a> interface for the audio session.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionManager">IAudioSessionManager Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />