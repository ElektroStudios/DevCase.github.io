# IAudioSessionEvents.OnChannelVolumeChanged Method 
 

Notifies the client that the volume level of an audio channel in the session submix has changed.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult OnChannelVolumeChanged(
	uint channelCount,
	IntPtr newVolumes,
	uint channelIndex,
	in Guid refEventContext
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function OnChannelVolumeChanged ( 
	channelCount As UInteger,
	newVolumes As IntPtr,
	channelIndex As UInteger,
	ByRef refEventContext As Guid
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IAudioSessionEvents
Dim channelCount As UInteger
Dim newVolumes As IntPtr
Dim channelIndex As UInteger
Dim refEventContext As Guid
Dim returnValue As HResult

returnValue = instance.OnChannelVolumeChanged(channelCount, 
	newVolumes, channelIndex, refEventContext)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult OnChannelVolumeChanged(
	[InAttribute] unsigned int channelCount, 
	[InAttribute] IntPtr newVolumes, 
	[InAttribute] unsigned int channelIndex, 
	[InAttribute] Guid% refEventContext
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract OnChannelVolumeChanged : 
        channelCount : uint32 * 
        newVolumes : IntPtr * 
        channelIndex : uint32 * 
        refEventContext : Guid byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>channelCount</dt><dd>Type: System.UInt32<br />The channel count.</dd><dt>newVolumes</dt><dd>Type: System.IntPtr<br />An array of volumnes cooresponding with each channel index.</dd><dt>channelIndex</dt><dd>Type: System.UInt32<br />The number of the channel whose volume level changed.</dd><dt>refEventContext</dt><dd>Type: System.Guid<br />A user context value that is passed to the notification callback.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionEvents">IAudioSessionEvents Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />