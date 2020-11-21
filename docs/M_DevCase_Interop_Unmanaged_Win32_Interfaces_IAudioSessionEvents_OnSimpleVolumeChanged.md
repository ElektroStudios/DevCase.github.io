# IAudioSessionEvents.OnSimpleVolumeChanged Method 
 

Notifies the client that the volume level or muting state of the session has changed.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult OnSimpleVolumeChanged(
	float volume,
	bool isMuted,
	in Guid refEventContext
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function OnSimpleVolumeChanged ( 
	volume As Single,
	isMuted As Boolean,
	ByRef refEventContext As Guid
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IAudioSessionEvents
Dim volume As Single
Dim isMuted As Boolean
Dim refEventContext As Guid
Dim returnValue As HResult

returnValue = instance.OnSimpleVolumeChanged(volume, 
	isMuted, refEventContext)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult OnSimpleVolumeChanged(
	[InAttribute] float volume, 
	[InAttribute] bool isMuted, 
	[InAttribute] Guid% refEventContext
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract OnSimpleVolumeChanged : 
        volume : float32 * 
        isMuted : bool * 
        refEventContext : Guid byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>volume</dt><dd>Type: System.Single<br />The new volume level for the audio session.</dd><dt>isMuted</dt><dd>Type: System.Boolean<br />The new muting state.</dd><dt>refEventContext</dt><dd>Type: System.Guid<br />A user context value that is passed to the notification callback.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionEvents">IAudioSessionEvents Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />