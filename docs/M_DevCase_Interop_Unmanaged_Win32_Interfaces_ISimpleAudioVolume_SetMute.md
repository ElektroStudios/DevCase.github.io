# ISimpleAudioVolume.SetMute Method 
 

Sets the muting state for the audio session.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult SetMute(
	bool isMuted,
	Guid eventContext
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function SetMute ( 
	isMuted As Boolean,
	eventContext As Guid
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As ISimpleAudioVolume
Dim isMuted As Boolean
Dim eventContext As Guid
Dim returnValue As HResult

returnValue = instance.SetMute(isMuted, 
	eventContext)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult SetMute(
	[InAttribute] bool isMuted, 
	[InAttribute] Guid eventContext
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract SetMute : 
        isMuted : bool * 
        eventContext : Guid -> HResult 

```


#### Parameters
&nbsp;<dl><dt>isMuted</dt><dd>Type: System.Boolean<br />The new muting state.</dd><dt>eventContext</dt><dd>Type: System.Guid<br />A user context value that is passed to the notification callback.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ISimpleAudioVolume">ISimpleAudioVolume Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />